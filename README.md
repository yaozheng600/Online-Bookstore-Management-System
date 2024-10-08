# Online-Bookstore-Management-System
## 1. Introduction
The Online Bookstore Management System is a Java-based backend system that allows users to browse, search, and purchase books online. The system also includes an admin panel for managing books, inventory, and orders. It is designed using Spring Boot, JPA, and MySQL as the main technologies.

## 2. System Features
### 2.1 User Management
Users can register and log in to the system.

Roles include Customer and Admin.

Admins can manage books, categories, and orders.
### 2.2 Book Management
Admins can add, edit, and remove books from the inventory.

Each book has details such as title, author, price, description, and stock quantity.
### 2.3 Shopping Cart
Customers can add books to their cart, modify the quantity, and remove items.

The system tracks the cart content for each user session.
### 2.4 Order Management
Customers can place orders from their shopping cart.

Admins can view and manage all customer orders.

Order status includes Pending, Shipped, and Completed.
### 2.5 Book Search & Filtering
Users can search for books by title, author, or category.

The search results are paginated and can be sorted by price or popularity.
### 2.6 Security & Authentication
The system uses JWT for user authentication.

Admin and customer roles have distinct access privileges.
## 3. Non-functional Requirements
The system should be scalable and able to handle multiple users concurrently.

All sensitive data, such as passwords, must be encrypted.

The system should provide a user-friendly interface for admins and customers.
## 4. Technologies Used
Backend: Spring Boot, Spring Security, Spring Data JPA

Database: MySQL

Authentication: JWT

Version Control: Git & GitHub

Build Tool: Maven
## 5. Project Goals
To showcase Java backend development skills using modern frameworks like Spring Boot.
To demonstrate knowledge in REST API design, authentication, database interaction, and deployment.
