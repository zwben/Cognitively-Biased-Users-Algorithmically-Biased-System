# Cognitively-Biased-Users-Algorithmically-Biased-System

### This repository contains a notebook for the analysis in the study: Cognitively Biased Users Interacting with Algorithmically Biased Results in Whole-Session Search on Debated Topics

### Used variables

**demographic **
`'ResponseId', 'Gender', 'Age', 'Commitment',`
**pre task attitude, information source, prior knowledge, openness**
`'Attitude_1', 'Source', 'Knowledge_1', 'Pre tolerance',`
**post query attitude, perceptions diversity and familiarity**
```
'Post q1 attitude_1', 'Post q1 perception_1', 'Post q1 familiarity_1', 
'Post q2 attitude_1', 'Post q2 perception_1', 'Post q2 familiarity_1',
'Post q3 attitude_1', 'Post q3 perception_1', 'Post q3 familiarity_1',
```
**post task explanation**
```
'Explain q1 click', 'Explain q1 click_10_TEXT', 'Explain q1 mark', 'Explain q1 mark_10_TEXT',
'Explain q2 click', 'Explain q2 click_10_TEXT', 'Explain q2 mark', 'Explain q2 mark_10_TEXT',
'Explain q3 click', 'Explain q3 click_10_TEXT', 'Explain q3 mark', 'Explain q3 mark_10_TEXT',
```
**flipped (the first query is biased) or not (balanced)**
`'QueryOrder',`
**task and topic conditions**
`'topic', 'topic_class', 'condition',`
**condition of each query**
`'random_q1', 'random_q2', 'random_q3',`
**interaction array**
```
'click_q1', 'dwelltime_q1', 'sequence_q1', 'bookmark_q1', 'more_q1',
'usefulness_q1', 'credibility_q1', 
'click_q2', 'dwelltime_q2', 'sequence_q2', 'bookmark_q2', 'more_q2', 
'usefulness_q2', 'credibility_q2',
'click_q3', 'dwelltime_q3', 'sequence_q3', 'bookmark_q3', 'more_q3', 
'usefulness_q3', 'credibility_q3',
```
**attidute direction and strength**
`'Att_direct', 'Att_strength',`
**directional attitude changes**
`'att_change_q1', 'att_change_q2', 'att_change_q3',`
**absolute attitude changes**
`'att_step_q1', 'att_step_q2', 'att_step_q3', 'att_step_total',`
**direction of selected query's attitude**
`'q1_direct_att', 'q2_direct_att', 'q3_direct_att',`
**aggregated interaction**

```
'click_q1_sum', 'click_q2_sum', 'click_q3_sum',
'bookmark_q1_sum', 'bookmark_q2_sum', 'bookmark_q3_sum',
'dwelltime_q1_sum', 'dwelltime_q2_sum', 'dwelltime_q3_sum',
'usefulness_q1_sum', 'usefulness_q2_sum', 'usefulness_q3_sum',
'credibility_q1_sum', 'credibility_q2_sum', 'credibility_q3_sum',
'click_q1_rank', 'click_q1_depth',
'click_q2_rank', 'click_q2_depth',
'click_q3_rank', 'click_q3_depth',
'bookmark_q1_avg', 'bookmark_q2_avg', 'bookmark_q3_avg',
'dwelltime_q1_avg', 'dwelltime_q2_avg',  'dwelltime_q3_avg',
'usefulness_q1_avg', 'usefulness_q2_avg', 'usefulness_q3_avg',
'credibility_q1_avg', 'credibility_q2_avg', 'credibility_q3_avg',
```
**proportion of interaction on attitude-confirming results**
```
'click_q1_prop', 'click_q1_prop_nor', 'dwelltime_q1_prop',
'usefulness_q1_prop', 'credibility_q1_prop',
'click_q2_prop', 'click_q2_prop_nor', 'dwelltime_q2_prop',
'usefulness_q2_prop',  'credibility_q2_prop',
'click_q3_prop', 'click_q3_prop_nor', 'dwelltime_q3_prop',
'usefulness_q3_prop', 'credibility_q3_prop'
```



### Publication
```
@inproceedings{wang2024cognitively,
author = {Wang, Ben and Liu, Jiqun},
title = {Cognitively biased users interacting with algorithmically biased results in whole-session search on debated topics},
year = {2024},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
booktitle = {Proceedings of the 2024 ACM SIGIR International Conference on Theory of Information Retrieval},
location = {Washington, D.C., USA},
series = {ICTIR '24}
}
```
