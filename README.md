# Bellabeat-capstone-project

Ask questions:

Bellabeat's stakeholders wish to identify any trend in the Fitbit's data of a smart device usage. These trends could possibly apply to Bellabeat customers as well as influence future marketing strategy. 

Stakeholders:

•	Main stakeholders: Bellabeat’s cofounder and chief creative officer Urška Sršen 
•	Other stakeholders: Sando Mur (Mathematician and Bellabeat’s cofounder, a key member of the executive team.
•	Bellabeat marketing analytic team
•	Bellabeat future customers

Prepare: 

The data is obtained through a survey via Amazon Mechanical Turk between 03.12.2016-05.12.2016. Thirty eligible Fitbit users consented to the submission of personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. The data seems reliable, original, comprehensive, cited since it is filled out by the users and the company doesn’t usually modify the data, and it is cited that the data is from a specific source; however, the data is not very current. It is a bit outdated since it is established in 2016. 
According to Kaggle, the dataset’s licensing is CC0, that means there is no copyright, so it is free to use. We can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission. 
Most dataset published on Kaggle is trustable and the upvote allows users to see how popular the dataset is. This is also an indication whether the dataset is reliable.
The dataset contains daily usage of the smart device of many customers. We can use the data in order to answer many questions regarding any possible business strategies

Dataset’s limitations: 

The limitation of the dataset is that it is a bit outdated (2016) and it is only collected from one source (Amazon Mechanical Turk). The data doesn’t represent the female population, which might not be very helpful for our analysis since the Bellabeat only sells products for females. Men and women are very different physically. Women are more susceptible to hormonal changes due to PMS, perimenopause, child-bearing problems. Our physical activities are often compromised because of these changes. It also doesn’t show age, income, and geographical location of the participants. These factors are very important regarding the usability of the products. In addition, certain information wasn’t provided by all the participants in the survey, for example, the weight info. There are only 8 people out of 30 who had reported their weight. The weightloginfo data is too small to carry out any analysis. 
I have done more research on finding additional data in order to carry out the analysis. I found a dataset related to physical activities on CDC website BRFSS: Table of Physical Activity. The data was collected from 2011 – 2021.  The participants were asked whether they had had any physical activities during the past month (from aerobic to strength related exercises).  It also includes age, gender, household income ,and geographic locations in the US. We can use this dataset in order to find any pattern regarding how women participate in any physical activities and the age group of people which participates the most. Although we can’t identify the age group for the female population (the Break_Out column identifies either the age group or the gender but not both), we can still get a better idea which age group exercises the most in general. The company can eventually develop business strategies targeting those groups. 

Cleaning:

I have used google spreadsheet to clean and organize certain parts of the dataset, then I used R to do the rest. Certain problems are easier to fixed with spreadsheet, like changing column names, verifying the length of the cells with the len function etc. 


Analyse:
According to the data, users lost more calories with higher intensity and a greater number of steps taken. That makes sense since the more you move, the more calories you spend. 
People who spent more time in bed usually sleep longer, but surprisingly there are a few outliers. Certain users spent over 1000 minutes in bed and their sleep duration was only 600 minutes. That means some of them might have some underlying health conditions, like insomnia, and back pain that might prevent them from falling asleep. 
Users tend to work out in midday, in the evening during the weekends, especially on Saturdays. That means Bellabeat can use this information in order to develop strategies for their customers

Recommendation for Bellabeat:
The analysis shows that users tend to be more active in midday and in the evening and Saturday looks like the most active day of the week. Bellabeat should offer users extra bonus on those period and Saturdays, for example, if user reaches a certain number of steps; they can get a discount on another product or even a free subscription for a period. That will encourage users to reach their goal and get a reward at the same time. Subscription is usually the most profitable revenue in business. If the company can convince a user to subscribe their service, the company will have a long term and stable revenue. 
Bellabeat should also take the menstruation period into account. During those periods, women tend to be more tired, so they might not be able to reach the daily goal. In order to encourage users to try harder after their period, the company can reward them by giving them bonuses. 

