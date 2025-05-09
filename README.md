# submit50-cs50-problems-2025-x-project

# Simple CalorieTrack

#### Video Demo: [[https://studio.youtube.com/video/RESWpJY6EK0](https://youtu.be/75-FM5opqEg)]

#### Description:

Simple CalorieTrack is a mobile app built for Android that helps users monitor their daily nutrition and exercise routines. Inspired by popular health tracking apps but tailored for simplicity and clarity, it allows users to log meals, calculate calories, and track fitness activities. The app provides personalized feedback based on user progress and displays weekly charts to show trends.

## Features


- Record running or workout sessions
- Calculate pace and total calories burned
- Store data persistently using SQLite

## Files

- `MainActivity.java`: Landing screen with options to log food or exercise
- `LogWorkoutActivity.java`: Captures duration, distance, and weight to compute calories
- `DatabaseHelper.java`: Manages SQLite storage
- `activity_*.xml`: Layout files for each screen
- `README.md`: Project description and documentation

## Tools Used

- Java (Android SDK)
- SQLite for local storage
- Android Studio

## Design Notes

We debated storing user history in flat JSON vs SQLite. SQLite offered more efficient querying and scalability. For feedback, we created motivational alerts based on thresholds (e.g., “you met your calorie goal today!”).

## AI Usage

ChatGPT was used to generate some helper methods and validate SQLite query structure. All usage was reviewed, edited, and cited in code comments where relevant.
