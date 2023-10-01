## Pizza-Restaurants
The Pizza Restaurant API is a Flask-based web service that allows users to interact with a database of restaurants and pizzas. It provides various endpoints for creating, retrieving, updating, and deleting restaurant and pizza information.

## Table of content
Installation requirement
Technology used
Models
Validations
Routes
Licence
Authors info

## Installation process
Git clone the repository to your local machine using the command https://pizza-restaurant-rr4m.onrender.com
To install the necessary dependencies run pipenv install,pip install sqlalchemy,pip install flask,pip install flask-migrate,pip install sqlalchemy_serializer 
Install the requirement packages using pip pip install sqlalchemy faker

## Models
Restaurant: Represents a restaurant with attributes such as name and address.
Pizza: Represents a pizza with attributes like name and ingredients.
RestaurantPizza: Represents the relationship between restaurants and pizzas, including the price.

## Validations
RestaurantPizza: Price must be between 1 and 30.
Restaurant: Must have a name less than 50 characters and must be unique.

## Routes
The API exposes the following routes:

GET /restaurants: Returns a list of restaurants in JSON format.
GET /restaurants/🆔 Returns information about a specific restaurant along with its pizzas.
DELETE /restaurants/🆔 Deletes a restaurant and its associated restaurant-pizzas.
GET /pizzas: Returns a list of pizzas in JSON format.
POST /restaurant_pizzas: Creates a new restaurant-pizza association.

## Testing
Test the implemented endpoints using postman and ensure they function as specified.

## Technologies used
python Flask SQLAlchemy

## License
MIT license

## Authors Information
Winny Chelangat