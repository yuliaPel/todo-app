# TodoApp

This is a simple TODO application built with React, offering essential task management features such as status filtering, task deletion, inline editing, and saving tasks to `localStorage`.

## Features

- **Add Tasks**: Enter a task in the text field and press Enter to add a new task to the list.
- **Toggle Task Status**: Each task can be marked as completed or incomplete using a checkbox.
- **Filter Tasks**: Filter tasks by status (All, Active, Completed).
- **Delete Tasks**: Click the "x" button to delete a task.
- **Clear Completed Tasks**: Button to remove all completed tasks (enabled only if there are completed tasks).
- **Edit Task Inline**: Double-click on a task to edit its title. Changes are saved on Enter or when the input loses focus, and tasks with empty titles are automatically deleted.
- **Toggle All Tasks**: A checkbox to toggle the status of all tasks (mark all as completed or not completed).

## Technologies

- **React**: A JavaScript library for building user interfaces.
- **React Context API**: Used to manage the state of tasks.
- **Bulma**: A CSS framework for styling the application.
- **FontAwesome**: An icon library for adding visual elements.
- **SCSS**: Used for writing styled components.

## Installation and Running

1. Clone the repository:
    ```bash
    git clone https://github.com/yuliaPel/todo-app.git
    cd todo-app
    ```
2. Install dependencies:
    ```bash
    npm install
    ```
3. Start the project:
    ```bash
    npm start
    ```
    Open your browser and go to http://localhost:3000 to view your application.

## Demo Link

- [DEMO LINK](https://yuliaPel.github.io/todo-app/)
