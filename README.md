# 🖼️ React Meme Generator

This is a simple meme generator built with React. Users can input custom top and bottom text, and generate random meme images using the Imgflip API.

## 🚀 Features

* Fetches meme templates from the [Imgflip API](https://api.imgflip.com/get_memes)
* Displays a randomly selected meme image on button click
* Allows users to enter custom top and bottom text for the meme

## 🧱 Built With

* React (useState, useEffect)
* HTML & CSS
* Imgflip API

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/react-meme-generator.git
cd react-meme-generator
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm start
```

Open your browser at `http://localhost:3000` to use the app.

## 🛠️ How It Works

* The `useEffect` hook fetches an array of meme templates from the Imgflip API when the component mounts.
* The user can click the "Get a new meme image 🖼" button to randomly select a meme image from the fetched list.
* Input fields let the user type in top and bottom text which will be displayed over the meme image.


