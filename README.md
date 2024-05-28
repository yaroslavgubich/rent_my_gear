Rails app generated with [lewagon/rails-templates](https://github.com/lewagon/rails-templates), created by the [Le Wagon coding bootcamp](https://www.lewagon.com) team.



## Running the Application

1. **Start the Rails server:**
    rails server

2. **Access the application:**
    Open your browser and navigate to `http://localhost:3000`

## Routes

### Users

- `GET /users` - List all users
- `GET /users/:id` - Show a user
- `POST /users` - Create a new user
- `PATCH/PUT /users/:id` - Update a user
- `DELETE /users/:id` - Delete a user

### Gears

- `GET /gears` - List all gears
- `GET /gears/:id` - Show a gear
- `POST /gears` - Create a new gear
- `PATCH/PUT /gears/:id` - Update a gear
- `DELETE /gears/:id` - Delete a gear

### Orders

- `GET /users/:user_id/orders` - List all orders for a user
- `GET /gears/:gear_id/orders` - List all orders for a gear
- `POST /orders` - Create a new order
- `PATCH/PUT /orders/:id` - Update an order
- `DELETE /orders/:id` - Delete an order

## Contributing

We welcome contributions to the Rent My Gear project. To contribute, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
