# Amazon-Reviews-Analysis
	In this repository, my objective is to investigate reviews from Amazon's vine program to see if they are valuable and/or trustworthy. Vine is basically a program where Amazon pays users to write reviews. What I would like to investigate is whether the users who are being paid as part of the Vine program are taking their responsibility of writing quality reviews seriously. To investigate this, I looked at some reviews data on video games that were purchased on Amazon. The reviews data for these games are stored in S3 buckets. I used PySpark to read the data from these S3 buckets and to then render dataframes displaying the data. Once I had the data into dataframes, I was then able to investigate trends and form some conclusions about the vine program.
	The dataset used was quite large; there were 1,785,997 reviews in it. The areas within the reviews that I would like to focus on are the paid reviews and unpaid reviews. For the paid reviews, 48.44% of these reviews were given a 5 star rating. For the unpaid reviews, 38.06% were given a 5 star rating. Immediately we can see that the the paid reviews (reviews written by users who were part of Vine) had more high quality reviews as rated by other users. However, I would still stay that the difference is small. In a dataset this large, a 10% difference in percentage of 5 star reviews is a significant one, but not a massive, attention-grabbing one. I would still come away with the conclusion that vine reviews are of slightly higher quality than non-vine reviews. One encouraging thing we can see from these numbers though is that vine reviewers are taking the writing of their reviews seriously. They are receiving a signficantly more 5-star ratings on their reviews than the non-vine reviewers, meaning the incentives provided in the vine program are working to make users write more meaningful reviews. Therefore, to answer the original question at the beginning of the project of whether vine reviews are valid/trustworthy, I would say "yes". Should a buyer trust them 100%? Of course not. A buyer should still be skeptical to a degree of anything sold online. However, a buyer can now know that at least what is written in the vine reviews is worth reading because these reviews are indeed being taken seriously by those who are writing them. 