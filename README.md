# Netflix Content Analysis: Storytelling Through Data Visualization

## Project Overview

This project demonstrates how data visualization can transform raw data into meaningful insights. Using the Netflix Movies and TV Shows dataset, various visualizations were created to analyze content distribution, release trends, audience ratings, and popular genres. The objective is to communicate findings through an engaging data story rather than simply presenting charts.

---

## Objective

The main objectives of this project are to:

- Analyze Netflix's content library.
- Create meaningful visualizations using Python.
- Identify important trends and patterns.
- Interpret visualizations using business insights.
- Demonstrate the importance of storytelling in data science.

---

## Dataset Information

**Dataset:** Netflix Movies and TV Shows

The dataset contains information about Netflix content, including:

- Type (Movie / TV Show)
- Title
- Director
- Country
- Release Year
- Rating
- Genre
- Duration

### Dataset Preparation

Before visualization:

- Missing values were identified.
- Missing values in categorical columns were replaced with **"Unknown"**.
- The dataset was checked for consistency and prepared for analysis.

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Visualizations Created

### 1. Movies vs TV Shows

A bar chart comparing the number of Movies and TV Shows available on Netflix.

**Insight:**

Movies make up the majority of Netflix's content library, showing the platform's stronger focus on films.

---

### 2. Top 10 Countries Producing Netflix Content

A bar chart displaying the countries with the highest number of Netflix titles.

**Insight:**

The United States contributes the largest number of titles, followed by India and other countries, highlighting Netflix's strong international presence.

---

### 3. Content Rating Distribution

A pie chart showing the percentage distribution of different Netflix content ratings.

**Insight:**

TV-MA is the most common rating, indicating that a significant portion of Netflix's content is intended for mature audiences.

---

### 4. Release Year Trend

A line chart showing the number of titles released each year.

**Insight:**

Netflix's content library experienced rapid growth after 2015, reflecting increased investment in original and licensed content.

---

### 5. Top Genres on Netflix

A bar chart displaying the ten most common genres available on Netflix.

**Insight:**

Drama, International Movies, and Comedy are among the most popular genres, demonstrating Netflix's diverse entertainment offerings.

---

## Key Findings

- Movies dominate Netflix's content library.
- The United States is the leading producer of Netflix content.
- Netflix experienced significant content growth after 2015.
- TV-MA is the most common content rating.
- Drama and International Movies are among the most frequently available genres.
- Data visualization makes it easier to identify patterns and communicate insights effectively.

---

## Business Interpretation

The visualizations indicate that Netflix has expanded into a global entertainment platform by:

- Investing heavily in movie production and licensing.
- Producing content across multiple countries.
- Offering diverse genres to appeal to a global audience.
- Focusing on mature audiences while maintaining family-friendly content.
- Continuously increasing its content library to meet subscriber demand.

---

## Project Workflow

1. Import required libraries.
2. Load the Netflix dataset.
3. Explore the dataset.
4. Clean missing values.
5. Create visualizations.
6. Interpret each visualization.
7. Build a complete data story.
8. Present key findings and business insights.

---

## Repository Structure

```
Netflix-Content-Analysis/

│── README.md
│── netflix_storytelling.ipynb
│── Netflix_Data_Storytelling_Presentation.pptx
│── netflix_titles.csv
```

---

## How to Run the Project

### Install Required Libraries

```bash
pip install pandas matplotlib seaborn
```

### Open the Notebook

Run the following notebook:

```
netflix_storytelling.ipynb
```

Execute all cells in sequence to reproduce the analysis and visualizations.

---

## Learning Outcomes

Through this project, I learned:

- How to clean data before visualization.
- How to choose the appropriate visualization for different types of data.
- How to create visualizations using Matplotlib and Seaborn.
- How to interpret charts instead of only creating them.
- How to communicate insights using data storytelling.
- How visualization supports business decision-making.

---

## Conclusion

This project demonstrates that effective data visualization is more than creating attractive charts—it is about communicating insights in a clear and meaningful way. By analyzing Netflix's content library, the project highlighted trends in content type, production countries, audience ratings, release years, and genres. The visualizations collectively tell the story of Netflix's growth as a global streaming platform and showcase the value of storytelling in data science.
