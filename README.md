# Investigating Netflix Movies

### Overview
This project explores Netflix’s data with a focus on analyzing movies released during the 1990s. The main objective is to identify key characteristics of 90s cinema, such as typical movie durations and patterns within specific genres— action movies. 

The following tools and libraries were used:
  - Pandas: for data manipulation and filtering
  - NumPy: for logical operations
  - Matplotlib: for visualizing distributions (histograms)

### Data Source
Data is sourced from a CSV file named netflix_data.csv which contains information about Netflix shows and movies, including columns like title, genre, release year, and duration.

### Analysis Steps
1. The dataset has been loaded with pandas.
   
2. Data Cleaning & Filtering Steps:
   - Removed all non-movie entries.
   - Filtered movies released between 1990 and 1999.

3. Analysis and Visualization
   - Duration Distribution of 1990s Movies
     - The analysis focused on exploring the distribution of movie durations for titles released between 1990 and 1999.
     - To visualize this, a histogram was created to reveal how movie lengths varied throughout the decade.
   - Zooming in on the Action Genre
     - A more focused analysis was conducted on movies from the Action genre released in the 1990s.
     - Specifically, the goal was to determine how many of these action films had a runtime of less than 90 minutes
   
4. Conclusion
   - Successfully filtered and explored a relevant subset of Netflix data.
   - Focused on 1990s movies for genre and duration analysis.
   - Found that short action films were relatively uncommon.
   
   
