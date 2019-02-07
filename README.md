## SimpleSpeechRecognizer: Prediction of word (one out three) from its pronunciation using ConvNet  
Cloned from github repository (https://github.com/manashmndl/DeadSimpleSpeechRecognizer). Train data sets are the same as that of the original work and  can be obtained from the `manashmndl/DeadSimpleSpeechRecognizer` repository.
Changes from the original work is the use of `tf.data` for pipeline building (ex: MFCC features resuting from pre-processing of wave format data are saved to tfrecords files. During training, data is read into tf.data.Dataset from tfrecords files)
