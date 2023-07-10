Module #5 Practical Application Assignment 5.1

Customer Coupon Acceptance Study

In this practical application assignment, I studied the customer coupon acceptance for the cheap restaurant ‘'Restaurant (<20)' coupon. 

1.	Data Preparation and Examination

I performed some data preparations before started. Firstly, I cleaned the data and created new dataframe that contains only the Restaurant (<20) coupons. Secondly, I examined the data by calculating the proportion of cheap restaurant coupons were accepted. Thirdly, I compared the acceptance rate between those who went to a cheap restaurant 3 or fewer times a month to those who went more. The result shows that people went to a cheap restaurant 4 or more times have slightly higher acceptance rate of coupon, however the difference is not substantial. 
After these preparation and examination, I conducted the customer coupon acceptance study from three different perspectives.

2.	The influence of contextual attributes to coupon acceptance

Contextual attributes can impact people’s behavior of accepting coupons. In the study, I chose four attributes of destination, weather, temperature and time.
Using Seaborn barplot() for visualization, I generated the plots of the destination, weather, temperature and time vs coupon acceptance and displayed these them in a 2x2 grid fashion.

From these four graphs, we can draw the conclusions that people are more likely to accept cheap restaurant coupons in these conditions:
•	No urgent place for destination
•	Sunny weather
•	Higher temperature
•	In the afternoon or before lunch time

These results of the contextual attributes influence for people accepting cheap restaurant coupons make sense in real life.
 
3.	The influence of user attributes to coupon acceptance

User attributes can strongly influence people’s behavior of accepting coupons. I chose the user attributes including marital status, income and number of times of visiting cheap restaurants in the study.
The group I chose are those whose marital status are either single or divorced, with income level less than 50K/per year. 
For visualization, I used the Seaborn histogram to show people who in this group the number of times of visiting cheap restaurants.

From the graph, we can draw the following conclusions. That is for people in single or divorced marital status with income less than 50K, with regard to the number of times of going to cheap restaurant:
•	People who go to cheap restaurant 1 to 3 times are more likely accepting the coupon
•	People who never go to cheap restaurant are less likely accepting the coupon
•	People who go to cheap restaurant other than above are slightly in favor of accepting the coupon depending on other factors.
 
4.	The influence of mixed contextual and user attributes to coupon acceptance

In this study, I chose two separate groups of contextual and user attributes.
Group 1 includes people who go to a cheap restaurant more than once a month and are single or divorced. In this group, I examined the influence of education to people’s coupon acceptance by using pie plot for visualization.
From the graph, we can draw the following conclusions. For group 1 of people who go to a cheap restaurant more than once a month and are single or divorced, those with higher level education (some college, bachelors degree, graduate degree) are more likely to accept coupons as compared to those with lower level education.

Group 2 includes people who go to a cheap restaurant less than once a month or are married. In this group, I examined the influence of passenger to people’s coupon acceptance by using pie plot for visualization.
From the graph, we can draw the following conclusions. For group 2 of people who go to a cheap restaurant less than once a month or are married, those driving alone or with friends are more likely to accept coupons as compared to those driving with partners or kids.

5.	Final thoughts and next steps 

This assignment is a good exercise to apply the knowledge we’ve learned so far to a practical application of coupon acceptance. It utilizes many knowledge and skills such as data cleaning, visualization, programming as well the tool chains.
The next steps would be to expand these knowledge and skills by understanding the artificial intelligence and machine learning techniques to further enhance the ability to explore the real world. 
  
