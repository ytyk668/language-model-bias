The model is run using the [AWD LSTM language model](https://github.com/salesforce/awd-lstm-lm)

To run the bias scores on a text corpus -
+ `python fixed_context_bias_score.py filepath dm -w 100 -n 1
+ `python infinite_context_bias_score.py filepath dm -w 100 -n 1
