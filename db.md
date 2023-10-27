# Database Documentation

## Overview

This document provides an overview and documentation for the "MyDatabase" database. It includes details about the database schema, tables, and their respective columns.

## Database Schema

- **Database Name:** MyDatabase
- **Version:** 1.0
- **Author:** Your Name
- **Last Updated:** October 27, 2023

## Tables

### Table: Users

- **Description:** This table stores information about registered users.

#### Columns

1. `user_id` (Primary Key)
   - **Data Type:** Integer
   - **Description:** Unique identifier for each user.
2. `username`
   - **Data Type:** String
   - **Description:** The username chosen by the user.
3. `email`
   - **Data Type:** String
   - **Description:** User's email address.
4. `created_at`
   - **Data Type:** Date and Time
   - **Description:** Timestamp indicating when the user account was created.

### Table: Orders

- **Description:** This table stores information about customer orders.

#### Columns

1. `order_id` (Primary Key)
   - **Data Type:** Integer
   - **Description:** Unique identifier for each order.
2. `user_id` (Foreign Key)
   - **Data Type:** Integer
   - **Description:** References the
