#MUSIC GENRE CLASSIFICATION 



#####Sriram Sundaraj,Ajay Prasadh 

#####National Institute Of Technology,Trichy

###Introduction
	The intelligent machine is an evil genie, escaped from its bottle.
										-	BRIAN HERBERT & KEVIN J. ANDERSON, The Butlerian Jihad

Automatic music genre classification is an  application of artificial intelligence ,more specifically machine learning to build a system that predicts the genre of a song.It is fairly simple for a human being to identify the genre of a song ,one thinks about how fast the beat of the song is ,the mood the song and the video of the song etc .All these help create a mental picture of the song and  thus the genres associated with it are determined.Automatic genre classification can be useful to answer some very intersting problems like  making song recommendations,finding similiar songs ,finding people who will like that particular song etc.
	Intelligene and automation are the core ideas that drove us into making this sytem.

###Related Work

* Several models have been made to solve this problem like Music Genre Classification with the Million Song Dataset [1] ,which uses audio features and lyrical features .The Model builds a bag of words for the lyrical features.For the audio features ,they used the MFCC (Mel-frequency cepstral coefficients)[2].Their work was unique in how they used lyrical features.

* Another paper along the same lines is Automatic Musical Genre Classification Of Audio Signals [3] .A   Vector of size 9  (mean-Centroid, mean-Rolloff, mean-Flux, mean-ZeroCrossings, std-Centroid, std-Rolloff, std-Flux, std-ZeroCrossings, LowEnegry) was their MusicalSurfaceFeatures  vector.Rhythm features were determined and their model was built using both the vectors.
	Our work differs from the previous two with respect to the feature vector under consideration.The Song has been analyzed as a wave and as a song well .


* DataSet Description and analysis
* Figure-1 Dataset genrewise number of songs
* Features
* Figure-2 Feature Correlation Graph
* Models
* Logistic Regression,SVM,kthNearest 
* Results
* Figuer-3 Accuracy across genres
* Best Model
* Conclusion





#####References:
* 1. Music Genre Classification with the Million Song Dataset. Dawen Liang,Haijie Gu, and Brendan O’Connor.

* 2. M. Muller. Information retrieval for music and motion. In Springer, 2007.

* 3.[ George Tzanetakis,Georg Essl,Perry Cook.Automatic Music Genre Classification for audio signals ](http://ismir2001.ismir.net/pdf/tzanetakis.pdf)




