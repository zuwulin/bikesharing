# NYC CitiBike Bike Sharing App Analysis

## Objective

The current project was designed to analyze the trends and overall efficiency of the NYC CitiBike bike sharing business model. The analysis focused on the application's available usage data for the month of August in 2019, and consisted of 2,344,224 total bike rides to look at. An easy-to-read visualization booklet was created with Tableau software, and the final review presentation can be found here: [NYC CitiBike Ride Sharing Overview](https://public.tableau.com/app/profile/ari6117/viz/NYCCityBikeRideSharingOverview/NYCCitiBikeBikeSharingOverview?publish=yes).

## Results
The goal of the analysis was multifaceted. First, it was imperative to examine the descriptive statistics of the userbase, such as the gender composition, and the proportion of subscribed users against single-time customers. Second, the analysis was aimed at investigating which spots are considered more popular as the starting, as well as the ending points of people's bikesharing adventures (which, in return, could provide the company with an estimated idea on which locations might need an increase in bike numbers, and which locations could stay as they are). In addition, the analysis was also aimed at investigating the peak usage hours, both in general across the month, as well as separated by weekdays, investigated in relation to user genders, and a combination of the factors thereof.
The results of the investigation can be seen below:

### Top Starting Locations
<p align="center">
  <img src="https://user-images.githubusercontent.com/99566803/171084983-e129bffe-6e1b-4927-bcb5-10a6bc84d842.png" />
</p>
As can be seen in the picture above, NYC has a fairly evenly dispersed demand for bikesharing starting locations. Notice, however, that bigger and darker circles represent a higher number of starting entries, and therefore should be examined for potential increase of bikes provided in said locations.

### Top Ending Locations
<p align="center">
  <img src="https://user-images.githubusercontent.com/99566803/171085112-6d417397-98fd-4f18-ab40-33d24abbc8c3.png" />
</p>
In a similar manner, the trend for ending locations across NYC seems to be in congruence with the starting locations graph, which can indicate that people tend to end their bike rides in the same place where they started. This is an interesting (and useful) observation for the company, as it provides insight into the necessity (or, in this case, lack of thereof) of creating more "drop off" spots for people to leave their bikes at.

### Checkout Times for Users
<p align="center">
  <img src="https://user-images.githubusercontent.com/99566803/171085152-1861244a-31f9-4566-b710-36584bf1c522.png" />
</p>
Next, when looking at the average trip durations for all users across NYC in the first three hours of the day (arbitrary chosen timeframe), one can notice an interesting trend of people using the bikesharing app equally much for trips averaging 10 minutes just as much as they do for trips averaging 60 minutes during 12:00 - 12:59am, whereas for the other two following hours examined the trend seems to indicate people's preference to use bike-sharing services for longer periods of time, on average (approximately and exponentially increasing for each given minute).

### Checkout Times by Gender
<p align="center">
  <img src="https://user-images.githubusercontent.com/99566803/171085167-523b6490-9b98-4e84-8262-4ea8886b31bf.png" />
</p>
When looking at the same statistics divided by gender, however, the picture is very different (note: yellow line represents male users, blue line represent female users, and red line represents non-identified users). First, it becomes blatantly obvious that the overall usage data is severely skewed by the male population, as their time usage is almost identical to the overall users' time usage chart. Second, the use trends between female and non-identified users seem to be fairly similar, given the discrepancy in numbers. This might indicate, among other things, that the bike sharing app is so far more catered to the male, rather than the female, audience.

### Trips by Weekday
<p align="center">
  <img src="https://user-images.githubusercontent.com/99566803/171085187-8732c4b8-a6fa-4d32-a683-7738feb61178.png" />
</p>
Trip duration and popularity was also examined in a form of a heatmap, investigating the trends across weekdays on an hourly basis for all users combined. The results indicate that the most popular hours throughout the week seem to be around 8am on workdays (darker tile indicate higher usage), as well as around 5 and 6 pm. This can indicate that people tend to resort to bike sharing experience when travelling to and from their work. On the weekends, the the hours between 12pm to 6pm seem to be more popular than the early morning or late evening hours, indicating most likely people's preference to use bike share as a leisurely activity on the weekends.

### Trips by Gender
<p align="center">
  <img src="https://user-images.githubusercontent.com/99566803/171085202-8d88cbb1-9825-4c05-8842-34bdeb49c879.png" />
</p>
When looking at the same heatmap divided by gender usage, the trends are a little different. Despite a great difference in male to female user ratio, female trends, while less prominent, seem to be consistent with the male audience's - that is, both male and female users prefer to use bike sharing to commute to work, and to leisurely use it on the weekends. Due to the lack of data on non-identified gender users, the only trends that can be somewhat identified is their preference to use the bike sharing experience in the waking hours between 12pm and 6pm on the weekends, all in accord with the overall trend. Further investigation is, however, advised.

### User Trips by Gender by Weekday
<p align="center">
  <img src="https://user-images.githubusercontent.com/99566803/171085216-e5d6b5b4-8fab-45dc-9aba-e3f20197162c.png" />
</p>
Finally, the two heatmaps discussed above were combined together, and added in the examination alongside the users' customer type they belonged to (either one-time use customer or a subsriber). According to the analysis, subscribers are responsible for a bigger share of bike rides registered under the bike sharing application, with the majority of said users being male. Interestingly enough, the peak usage day for this group of users seems to be Thursday, followed closely by Friday. For female subscribers, Wednesdays seem to be an oddly placed off-day for bike sharing purposes. Further analysis is suggested.

## Summary
Overall, bike sharing seems to be a booming business model in the city of New York, with August 2019 being a great example of overally successful performance for the bike sharing company. Most of the rides were located around Manhattan Island, preferred by the male users, and used primarely during the rush hour commute (i.e., between 8-9am and 5-6pm), as well as during the daytime (12pm to 6pm) on the weekends. This suggests that bike sharing is an increasingly common practice that enables people to substitite public and private (car) transportation options when going to work, as well as when spending free time on the weekends.

### Future Analysis
Some potential analyses that could be performed in regards to the bike sharing phenomenon in NYC are:

* Examining the data for all twelve months of the year, in order to provide for a more complete and accurate picture of bike sharing (perhaps bikes are not as prominently popular during the winter season as they are in the summer);

* It might also be beneficial to compare the bike share location maps to subway stations' locations, in order to ameliorate the commute experience (in case people are biking to subway stations from a more remote location), as well as link the bike sharing usage trends with the weather data (simiarly to seasonal demand, people might be less prone to using bike share in, for example, rainy or windy conditions).
