# Coupon Purchase Prediction
 Past Project
A previous approach at a business case with another programming language, now using other more comfortable languages to approach this problem.

Previous commits include segregating data into 3 different clusters via kmeans, for better management of memory and sparsity of matrixes.

Item-to-item collaborative filtering across different coupons, for each unique user. 19413 users
Recommender Systems used with modified Cosine similarity distances of paired items.
- experimented with regular cosine similarity distances
- Centered Cosine similarity distances (chosen)

Future implementation : 
will include the use of SVD for dimensionality reduction of a highly sparse matrix: 100000 records, for a 10000x20000 matrix.
