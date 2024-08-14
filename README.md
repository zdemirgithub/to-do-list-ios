# To-Do List iOS App

## Overview

The **To-Do List** app is a simple and intuitive iOS application that allows users to manage their tasks effectively. Users can add new tasks, mark them as completed, and delete tasks they no longer need. This project is written in Swift and follows a basic MVC (Model-View-Controller) architecture.

## Features

- **Add Tasks**: Easily add new tasks with a simple user interface.
- **Mark as Completed**: Toggle tasks as completed or incomplete with a single tap.
- **Delete Tasks**: Swipe to delete tasks you no longer need.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/todo-list-app.git
   cd todo-list-app
   ```

2. **Open the project in Xcode**:
   - Open `ToDoListApp.xcodeproj` in Xcode.

3. **Run the app**:
   - Select a simulator or a connected device.
   - Click the **Run** button or press `Cmd + R`.

## Usage

1. **Viewing Tasks**: All tasks will be displayed in a list format on the main screen.
2. **Adding Tasks**: Tap the `+` button in the navigation bar to add a new task.
3. **Marking Tasks as Completed**: Tap on a task to toggle its completion status.
4. **Deleting Tasks**: Swipe left on a task to delete it from the list.

## Project Structure

- **ToDoItem.swift**: The data model representing a task with `title` and `isCompleted` properties.
- **ToDoListViewController.swift**: The main view controller managing the list of tasks. It includes logic for adding, marking, and deleting tasks.
- **AppDelegate.swift**: The entry point of the application, setting up the initial view controller.

## Requirements

- **iOS 13.0+**
- **Xcode 12.0+**
- **Swift 5.0+**



## Contributing

Feel free to fork this repository and submit pull requests. Any contributions to improve the app or add new features are welcome!

## Acknowledgments

This app was created as a learning project to demonstrate the basics of iOS app development with Swift.


This `README.md` covers the essential aspects of your app, including its functionality, setup, and usage. It also provides basic instructions on how to run and contribute to the project. You can customize it further based on your specific requirements.
