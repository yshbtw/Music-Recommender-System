# Music Recommender System

# Overview

The Music Recommender System is a robust and interactive application that provides song recommendations based on the lyrics of a selected song. It is built using a dataset of 50,000 songs from Spotify and leverages cosine similarity to identify songs with similar lyrical content. The system features an end-to-end user interface powered by Streamlit and integrates with the Spotify API to fetch song posters and additional metadata.

# Features

Lyrics-Based Recommendations: Suggests songs similar to the lyrics of the selected song.

Interactive UI: A user-friendly interface built using Streamlit for seamless interaction.

Spotify Integration: Fetches song details, posters, and metadata directly from Spotify.

Large Dataset: Utilizes a dataset of 50,000 songs, ensuring diverse and accurate recommendations.

# Technologies Used

Python: Core programming language.

Streamlit: For building the interactive web application.

Spotify API: For fetching song metadata and posters.

Pandas & NumPy: For data manipulation and preprocessing.

Scikit-learn: For implementing cosine similarity.

# Dataset

The dataset contains information on 50,000 songs from Spotify, including:

Song titles

Artist names

Lyrics

Genre

Metadata (e.g., release year, popularity)

# How It Works

Data Preprocessing:

The lyrics data is cleaned and vectorized to create a numerical representation using techniques like TF-IDF.

Cosine similarity is applied to calculate the similarity between songs based on their vectorized lyrics.

# User Interaction:

Users can select a song from the list or search for it.

The system computes the top N similar songs based on cosine similarity scores.

# Spotify Integration:

The Spotify API fetches posters and additional metadata for the recommended songs.

# Output:

A list of recommended songs is displayed along with their posters and metadata.

Installation

Prerequisites

Python 3.8+

Spotify Developer Account (to get the API credentials)

# Steps

Clone the repository.

Navigate to the project directory.

Install the required dependencies.

Set up Spotify API credentials:

Go to the Spotify Developer Dashboard.

Create an app and get your client_id and client_secret.

Save the credentials in a .env file.

Run the application.

# Usage

Open the Streamlit app in your browser.

Search for or select a song.

View the recommended songs along with their Spotify posters and metadata
