# sinc_net_proj2

I forked and ran sincnet on my machine and performed the following
1) Reproduced the results on a small subset of the TIMIT dataset. This took a long time and overheated my computer, even after I decided to only train/test on a small subset of the data. Make sure you update the data filepath if you want to run the code.
2) Ran the speaker_id.py on my own data. I adjusted the classes to 2, as I only used data with 2 classes.

In both cases I decreased the default number of epochs to 32, as there is a fast converge initially, with small incremental improvements in loss performance and classification error rate in the later epochs.
