## Project-Finding-Heavy-Traffic-Indicators-on-I-94
- **Objective**: Find and determine some indicators of heavy traffic.

### Metro Interstate Traffic Volume
`Dataset`: Hourly Minneapolis-St Paul, MN traffic volume for westbound I-94. Includes weather and holiday features from 2012-2018.<br>
`Available from`: https://archive.ics.uci.edu/dataset/492/metro+interstate+traffic+volume <br>

Variable Information: <br>
1. `holiday`: US National holidays plus regional holiday, Minnesota State Fair
2. `temp`: Average temp in kelvin
3. `rain_1h`: Amount in mm of rain that occurred in the hour
4. `snow_1h`: Amount in mm of snow that occurred in the hour
5. `clouds_all`: Percentage of cloud cover
6. `weather_main`: Short textual description of the current weather
7. `weather_description`: Longer textual description of the current weather
8. `date_time`: Hour of the data collected in local CST time
9. `traffic_volume`: Hourly I-94 ATR 301 reported westbound traffic volume

Learning source: `DataQuest`

### Conclusion
- Warmer months lead to heavier traffic, with July being an outlier due to certain events that occurred in 2016 (possibly construction work).
- Weekdays are more busy than weekends, with rush hours at 7 and 16h. Weekends are less busy, but it is still advisable to travel in the mornings when traffic is light.
- Finally, we couldn't find any strong correlations between `weather conditions` and `traffic volume`, other than weather conditions that severely affect road conditions or visibility.
