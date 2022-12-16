# recommendation system


<img width="216" alt="Whats-recommendation-sys_pic1" src="https://user-images.githubusercontent.com/57616193/208065858-c77a17ec-db1a-4242-b4c5-5c2402ac3620.png">


This project demonstrates how to build a recommendation system using the Nearest Neighbors algorithm and the TfidfVectorizer. The recommendation system is based on the view counts of items by different users and the descriptions of the items. The system takes in a user_id and returns a list of recommended items for that user. The Nearest Neighbors algorithm is used to find the similarity between items based on their descriptions, and the TfidfVectorizer is used to convert the item descriptions into numerical vectors. The recommendation scores for each item are calculated by summing the similarity scores of the similar items for each item in the list of items viewed by the user. The top 10 items with the highest recommendation scores are then returned as the recommendations for the user.




### The following libraries are used in this project:

pandas: Used for creating and manipulating dataframes

sklearn.neighbors: Contains the NearestNeighbors class which is used to find the nearest neighbors of a given item vector

collections: Contains the defaultdict class which is used to create a dictionary with a default value

sklearn.feature_extraction.text: Contains the TfidfVectorizer class which is used to convert the item descriptions into numerical vectors

numpy: Used for performing numerical operations such as reshaping arrays and checking for NaN values
