# Tree-enhanced Embedding Model
This is our project for the paper:
>Xiang Wang, Xiangnan He, Fuli Feng, Liqiang Nie and Tat-Seng Chua (2018). [TEM: Tree-enhanced Embedding Model for Explainable Recommendation](https://dl.acm.org/citation.cfm?id=3178876.3186066). In WWW'18, Lyon, France, April 23–27, 2018.

Author: Dr. Xiang Wang (xiangwang at u.nus.edu)

## Introduction
Tree-enhanced Embedding Mode (TEM) is a new recommendation framework, which combines the strong representation ability of embeddingbased and interpretability of tree-based models. At its core is an easy-to-interpret decision-tree and attention network, making the recommendation process fully transparent and explainable.

## Citation 
If you want to use our codes and datasets in your research, please cite:
```
@inproceedings{TEM2018,
  author    = {Xiang Wang and
               Xiangnan He and
               Fuli Feng and
               Liqiang Nie and
               Tat{-}Seng Chua},
  title     = {{TEM:} Tree-enhanced Embedding Model for Explainable Recommendation},
  booktitle = {{WWW}},
  pages     = {1543--1552},
  year      = {2018},
}
```
## Codes
We are finding license suitable to release this software. Currently codes are under request and will be released later.

## Dataset
We provide two processed datasets: London-Attractions (LON-A) and New-York-City-Restaurant (NYC-R) datasets.
* `London_Attractions_Complete_Review.csv`
  * All positive instances.
  * Each line is a review, where the fields of user profiles and item attributes start with 'u' and 'i', respectively.

* `New_York_City_Restaurant_Complete_Review.csv`
  * All positive instances.
  * Each line is a review, where the fields of user profiles and item attributes start with 'u' and 'i', respectively.
