# Key-Phrase-Matcher--NLP

# Describtion

Given a list of short text responses and a list of possible key phrases or group of key phrases with similar meaning. Assign key phrases or the group to relevant short text response. A key phrase can be assigned to multiple responses and similarly a response can be assigned multiple key phrases.


# Problem Statemtent

Find Similer keyphase in a corpus

# Constraints:
Has to understand the semantic relation between words and given keyphrase
No Latency Requirement

# Benefits:
Help to understand and transverse huge corpus


I have used 4 diffrent approches for the same with pre-trained model

* Glove - Good with words but not work well on phrases
* Doc2Vec - Slightly Improvement then GLove
* BERT 
* Phrase based matching

# Pretrained Doc2Vec 
  * 1. English Wikipedia DBOW (1.4gb)    https://ibm.ent.box.com/s/3f160t4xpuya9an935k84ig465gvymm2
  * 2. Associated Press News DBOW (0.6GB) https://ibm.ent.box.com/s/9ebs3c759qqo1d8i7ed323i6shv2js7e
  
 
 For more details kindly refer to the following
 *  Kivita Ganesan     https://kavita-ganesan.com/kavitas-tutorials/#.X-L5WOkzaYU
 *  https://towardsdatascience.com/cutting-edge-semantic-search-and-sentence-similarity-53380328c655
