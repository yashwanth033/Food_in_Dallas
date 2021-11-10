# FOODCOUVER: An exploratory data analysis on the food scene in Dallas, Texas, US

## Table of Contents
* [Background](#background)
* [Findings](#findings)
  * [Summary Statistics](#summary-statistics)
  * [Categorical Statistics](#categorical-statistics)
  * [Geographic Statistics](#geographic-statistics)
* [Usage](#usage)
* [Legality](#legality)

## Background

As a self-proclaimed "foodie" in Dallas, TX, I wanted to find out more than just how the food tastes, but the experience that my fellow residents (or tourists!) had within my own beloved city. I wanted to prove or disprove current ideas, such as how the best food comes from downtown, as well as find out new facts about the city I have been living in for the last 24 years. 


* Are we an expensive city to eat in? 


* On average, where are the highest rated restaurants located? 


* Which genre of cuisine is the most common to find? 


In this exploratory data analysis, I found out answers to these questions and more with my trusty friend; data.

## Findings

### Summary Statistics
![summarystatistics](https://user-images.githubusercontent.com/50093891/79916155-19146700-83dd-11ea-8559-ab08a5d642e9.png)
Here are the general summary statistics for restaurants in Dallas, TX, according to Yelp data. As we can see in the above graphs, most restaurants have < 500 reviews, most are within a rating of 4.0 - 4.5, and majority are given a double money sign in terms of price ($$).

### Categorical Statistics
![category](https://user-images.githubusercontent.com/50093891/80263801-b2928180-8646-11ea-9e51-1040f3e7592e.png)
Next, we will look at categorical data of the same properties. The graphs above show the top 5 for each property, but you will be able to see more results in the main project notebook. This data suggests that most categories are pretty close in terms of average price and rating. We have many NewAmerican restaurants in Dallas, TX.

### Geographic Statistics
Lastly, we have data for the areas of Dallas, TX for average rating, restaurant density, average price, and review count.

**Average Rating**
![average_rating](https://user-images.githubusercontent.com/50093891/79916236-3cd7ad00-83dd-11ea-8524-81051448bf93.png)<br />


**Restaurant Density**
![restaurant_density](https://user-images.githubusercontent.com/50093891/79916255-46611500-83dd-11ea-8d58-d0f3a522621b.png)<br />


**Average Price**
![average_price](https://user-images.githubusercontent.com/50093891/79916303-5842b800-83dd-11ea-837f-d5e70073cd59.png)<br />


**Review Count**
![review_count](https://user-images.githubusercontent.com/50093891/79916348-6b558800-83dd-11ea-9438-d92d6b1fc351.png)<br />
The location data is properly seperated based on zipcode, so we cannot make any conclusions based on geography.


## Usage

This project is best viewed in a notebook viewer, which can be accessed [here](https://nbviewer.jupyter.org/github/justinmlam/foodcouver/blob/master/foodcouver.ipynb). In this notebook, you will find a walk through of the work done and the respective code.

## Legality
This is a personal project made for non-commercial uses ONLY. This project will not be used to generate any promotional or monetary value for me, the creator, or the user.
* If you are a Yelp representative and there are any legal issues with this project, please contact me! *

This project uses the Yelp Fusion API, and terms and conditions are found here:
https://www.yelp.ca/developers/api_terms

"Allowable non-commercial use of the Yelp Content. Notwithstanding the foregoing, you may use the Yelp Content to perform certain analysis for non-commercial uses only, such as creating rich visualizations or exploring trends and correlations over time, so long as the underlying Yelp Content is only displayed in the aggregate as an analytical output, and not individually. For example, this is an acceptable non-commercial analytical use of the Yelp Content. “Non-commercial use” means any use of the Yelp Content which does not generate promotional or monetary value for the creator or the user, or such use does not gain economic value from the use of our content for the creator or user, i.e. you. If you are interested in commercial use of the Yelp Content, please visit www.yelp.com/knowledge."