#Models

Broadly stated,  models are the programmatic representation of the concepts and data that an application uses.  In a blogging application, these would be things like post, comments, and users.
In a store front, they might be products, costumers, shopping carts, sales, etc...
Merb was designed to give developers as much latitude as possible in describing their models.
Models can be anything a developer can represent with Ruby classes.

Having said this, the vast majority of applications will use some kind of [ORM](http://en.wikipedia.org/wiki/Object-relational_mapping) (Object Relational Mapper) to persist data between requests, and most will store their data in some form of a database.
The default Merb Stack uses DataMapper to communicate with an SQLite database.
This is an excellent choice for easy development of new projects.
Once in production, however, it is generally recommended that developers make the switch to one of the more powerful database engines like Postgres or MySQL.
Projects which are coming from the Rails world may wish to keep their ActiveRecord models; Merb supports this as well.
Having said this, the vast majority of application will use some kind of ORM (Object Relational Mapper) to persist data between requests; most apps will store their data in with some form of a database.
The default Merb Stack uses DataMapper to communicate with an SQLite database.
This is an excellent choice for easy development of new projects.

Once in production, however, it is generally recommended that developers make the switch to one of the more powerful database engines, such has Postgres or MySQL.

The rest of this chapter will focus on using DataMapper to create Model classes.

## Attributes

## Associations

## Callbacks
