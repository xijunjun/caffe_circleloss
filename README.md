# caffe_circleloss
caffe circleloss layer

message CircleLossParameter {
  optional float gamma = 1 [default = 256];
  optional float margin = 2 [default = 0.25]; 
}
