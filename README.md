# Tableau: Airbnb(Los Angeles)
With data provided by [Inside Airbnb](http://insideairbnb.com/get-the-data.html), an interactive dashboard is created for customers based on accommodation features.

## Data Source
1. [listings.csv.gz](http://data.insideairbnb.com/united-states/ca/los-angeles/2019-07-08/data/listings.csv.gz)<br/>
Detailed listings data such as amenities, zip code and room type. 

2. [listings.csv](http://data.insideairbnb.com/united-states/ca/los-angeles/2019-07-08/visualisations/listings.csv)<br/>
Summary information and metrics for listings sucha as name, price and number of reviews. 

3. [reviews.csv](http://data.insideairbnb.com/united-states/ca/los-angeles/2019-07-08/visualisations/reviews.csv)<br/>
Date of review and listing id. 

## Data Preprocessing
1. Create new boolean features for amenities. <br/>
   <img src="/images/amenities.png" alt="amenities" width=500>

2. Select features from each dataset. 
   ![listing2_features](/images/listing2_features.png)
   <img src="/images/listings_features.png" alt="listings_features" width=700>
   <img src="/images/reviews.png" alt="reviews" width=400>

3. Narrow down the dataset by selecting zip codes of 2 different areas. 


## Skills Acquired
* Pandas: e.g. cleaning data, creating new tables and features
* Tableau: e.g. using filters, parameters and pages to create interactive dashboard
