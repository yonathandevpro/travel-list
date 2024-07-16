# Travel List App

A simple and fun packing list application built with React.js. Plan your trips efficiently by adding, managing, and tracking your packing list items.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Components](#components)
  - [Logo](#logo)
  - [Form](#form)
  - [Item](#item)
  - [PackingList](#packinglist)
  - [Stats](#stats)
  - [App](#app)
- [Styling](#styling)
- [Contributing](#contributing)
- [License](#license)

## Features

- Add items to your packing list.
- Track the quantity of each item.
- Mark items as packed/unpacked.
- Sort items by input order, description, or packed status.
- Clear all items from the list.

## Installation

1. Clone the repository:

```sh
git clone https://github.com/yonathandevpro/travel-list.git
```
2. Navigate to the project directory:

```sh
cd travel-list
```
3. Install dependencies:

```sh
npm install
```
4. Start the development server:

```sh
npm run dev
```
## Usage

1. Open the application in your browser.
2. Use the form to add items to your packing list.
3. Mark items as packed/unpacked by clicking the checkbox.
4. Delete items from the list using the delete button.
5. Sort items using the dropdown menu.
6. Clear the entire list by clicking the "Clear list" button.

## Project Structure

```sh
TRAVEL-LIST/
├── public/
│   └── index.html
├── src/
│   ├── Components/
│   │   ├── Logo.jsx
│   │   ├── Form.jsx
│   │   ├── Item.jsx
│   │   ├── PackingList.jsx
│   │   └── Stats.jsx
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── package.json
└── vite.config.js
```
### public/index.html

The main HTML file that includes the root div for rendering the React application.

### src/Components/Logo.jsx

Component for displaying the application logo.

### src/Components/Form.jsx

Component containing the form to add new items to the packing list.

### src/Components/Item.jsx

Component representing an individual item in the packing list.

### src/Components/PackingList.jsx

Component that renders the list of items and provides sorting and clearing functionality.

### src/Components/Stats.jsx

Component that displays the packing statistics, such as the number of items packed and the total number of items.

### src/App.jsx

The main component that combines all other components and manages the state of the application.

### src/index.css

CSS file for styling the application.

### src/main.jsx

Entry point for the React application, rendering the App component into the root div.

## Styling

The application uses a combination of CSS and Google Fonts for styling. The main CSS file is located in `src/index.css`, and it imports fonts from Google Fonts for a unique and attractive design.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your changes.

1. Fork the Project.
2. Create your feature branch:

```sh
git checkout -b feature/AmazingFeature
```
3. Commit your changes:

```sh
git commit -m 'Add some AmazingFeature'
```
4. Push to the branch:

```sh
git push origin feature/AmazingFeature
```
5. Open a pull request.

## License

Distributed under the MIT License.

## Collaborations

Email me if you want to work together at:
```sh
yonathanber@icloud.com
```
