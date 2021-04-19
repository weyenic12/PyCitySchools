# PyCitySchools Challenge
---
## Overview of the School District Analysis
- We were given the task to analyze student grades from different high schools. For this challenge, our goal was to replace the incorrect math and reading scores for Thomas High School 9th graders while keeping the rest of the data intact.
---
## Results
- [Code](/PyCitySchools.ipynb)
- [School Summary Original](/Resources/school_summary.PNG) / [School Summary New](Resources/school_summary_new.PNG)
- As you can see by the original School Summary, the scores for '% Passing Math', '% Passing Reading', and '% Overall Passing' are all lower than they should be. We removed all the data for Thomas High School 9th graders and got a new school summary. You can see a much greater increase the amount of students passing reading, math and overall.
- We later sorted the schools by 'Spending Ranges Per Student', 'School Size', 'School Type' and class scores by grade among all the high schools. By removing the 9th grade data for Thomas High School, their data reads 'NaN' for their individual scores.
---
## Summary
- The updated School District analysis has four major changes. One being the total students as we removed the data for 9th graders at Thomas High School. The next would be the average scores for both math and reading as the data amount changed. Another change would be the % of students that passed math, reading and overall. This changed because of the incorrect data for 9th graders that we removed. The total data for the district changed a little with the removal of the 9th graders from Thomas High School; however, it did not have a big impact on the overall data as the size of the data from other schools was big.
---
