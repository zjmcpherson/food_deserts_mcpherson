# Food Deserts and Obesity Analysis
## About the Project
Obesity and food deserts are prevalent in the majority southern region of the United States. My main focus for this project is comparing the more urbanized Tennessee counties, to the rural counties, scattered across the state. I wanted to take the opportunity to do an exploratory analysis on the different factors that could be impacting each Tennessee County.

## Motivation:
I was raised in a poor, rural town with what seemed to be only fast-food choices around me and with inadequate city resources such as parks, walkable streets, and community centers. At a very early age, it became clear to me that eating healthy food and maintaining a balanced diet was **vital**, but it isn’t affordable for all households. In this analysis, I hope to find where cities can increase necessary resources for a healthier food environment.

## Data Questions
* What are the obesity rates for places with more accessibility to fast-food?
* What are the trends for urban vs rural food deserts? (Food desert being defined as a supermarket not within 10 miles for rural areas)
* Does obesity vary by income?
* How does obesity vary between Tennessee counties? 

* Stretch Question: Are there other states that have similar health trends as Tennessee?

## Normalizing the Data
Overall, the data was fairly clean, but the biggest obstacle was pulling specific Variable Codes from the Food Atlas. I utilized Python to create multiple subsets on each variable, then merged the subsets to a more usable dataframe. Since I chose a few different data sets, the years vary from 2011 - 2022. This shows a timeline on how elements of this analysis has changed.

## Technologies Used
1. Excel - Exploration of the data and referencing
2. Python/Pandas - normalization and specific aggregations on the dataset
3. Tableau - Visualizations and Data Story Telling

## Data Sources
To answer the questions listed above, I used the following sources:
1. Food Environment Atlas
    * https://www.ers.usda.gov/data-products/food-environment-atlas/data-access-and-documentation-downloads/
2. Obesity Rates for Selected Regions
    * https://www.countyhealthrankings.org/explore-health-rankings/tennessee/data-and-resources
3. Food Access Atlas
    * https://www.ers.usda.gov/data-products/food-access-research-atlas/download-the-data/
4. Income in the Past 12 months
    * https://data.census.gov/table?q=state+median+income&tid=ACSST5Y2021.S1901&moe=false
5. Obesity Rates by State
    * https://chronicdata.cdc.gov/Behavioral-Risk-Factors/BRFSS-Graph-of-Current-Adult-Obesity-Prevalence-Na/tcmp-75zb
    
## Tableau Story
https://public.tableau.com/views/food_deserts_obesity/FoodDesertsandObesity?:language=en-US&:display_count=n&:origin=viz_share_link