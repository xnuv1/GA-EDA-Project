# EDA-Project 
## Problem Statement:
The Olympic Games bring athletes from every corner of the world, yet only a small share of them win medals. In this project, we look at how age, height, and weight shape those outcomes and how these traits differ for men and women. We track participation across the last six Olympic Games, focusing on the balance between male and female athletes. And to show how much the Games have evolved, we compare the 1952 and 2016 Summer Olympics, highlighting how the profile of athletes especially women has shifted over time.
---

## Executive Summary 
We cleaned and prepared the Olympic athletes dataset by merging athlete records with country names, standardizing demographics, and handling missing values separately for men and women. This gave us a reliable dataset to explore patterns in participation, demographics, and medal outcomes.
  
Our analysis showed that male athletes dominated participation in earlier years, but female representation has grown steadily, especially in the last six Olympic Games. Comparing the 1952 and 2016 Summer Olympics, we found that female athletes compete in far greater numbers today, and their average age and height have shifted notably over time. These findings highlight both the progress in gender balance and the evolving profile of Olympic athletes.

---
 ## File Directory

 Code --> Code.ipynb
 
 Data --> Orgiginal Data:
             athelte_events.csv
             noc_regions.csv
          Cleaned Data:
              Cleaned.csv
              
Presentation --> Presentation.ppt

--

## Data and Data Dictionary

The data is provided by GA. It combines information on athletes, their demographics, events, and medal outcomes, covering the Olympic Games from 1896 to 2016. We merged this with the noc_regions.csv file to map each National Olympic Committee (NOC) code to a full country name.

Our final cleaned dataset includes the following features:

ID: Unique identifier for each athlete

Name: Athlete’s full name

Sex: Male or Female

Age: Age of the athlete (numeric, cleaned)

Height: Height in centimeters (numeric, cleaned)

Weight: Weight in kilograms (numeric, cleaned)

Team: Team name

NOC: National Olympic Committee code 

Country: Country name 

Games: Year + Season

Year: Year of the Olympic Games (engineered)

Season: Summer or Winter (engineered)

City: Host city

Sport: Sport category 

Event: Specific event 

Medal: Gold, Silver, Bronze, or No Medal (cleaned)

---
## Recommendations/Conclusion
- Gender differences in Olympic participation have steadily decreased over time, reflecting progress toward equity.
- Participation dropped in certain years due to global conflicts or political boycotts, most notably in the 1940s (World War II) and 1980s (Cold War tensions).
- The number of events available to female athletes has increased significantly in recent decades, signaling a global push to elevate women's sports.
- Age is a key performance factor: most Olympic medalists are under 35 years old, highlighting the physical peak period for elite competition.
- Summer Olympics consistently host more athletes and events than Winter Games, offering broader opportunities for gender equity and age diversity analysis.
- Winter medalists tend to be slightly older on average, especially in sports that rely more on skill and precision than raw physical exertion


## Areas for Further Research/Study

Our analysis centered on demographics, gender balance, and medal outcomes, but there are many ways this work could be extended. A natural next step would be to examine sport-specific differences, since the ideal profile of a gymnast is very different from that of a rower or weightlifter. Looking at performance trends across different sports or events could also show how certain physical traits align more closely with success in specific disciplines.

Another valuable direction is to take a deeper country-level view. By comparing demographic shifts within nations, we could better understand how training systems and investment in sports influence participation.

---

## Key Visualizations

Male vs female participation over time (last six Olympics) 

Male vs female participation over time over time

Medal counts by gender over time

Age, height, weight distributions by gender and medal status

1952 vs 2016 comparison 

