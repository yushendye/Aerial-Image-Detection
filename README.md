# Aerial-Image-Detection
### For this project I have used TTPLA tower dataset. The dataset can be downloaded from <a href = "https://github.com/R3ab/ttpla_dataset"> here </a>.

## Train mAP:
```
           Class            Images     Targets       P           R        mAP@.5  mAP@.5:.95
                 all         394         663       0.912       0.957       0.953       0.872
       tower_lattice         394         275       0.941       0.989       0.985       0.937
        tower_tucohy         394         170       0.875       0.947       0.939       0.854
        tower_wooden         394         218       0.919       0.936       0.934       0.824
```

## Validation data mAP
```
         Class              Images     Targets       P           R      mAP@.5       mAP@.5:.95
                 all          53         103       0.797       0.603       0.583       0.447
       tower_lattice          53          41       0.969       0.756       0.753        0.61
        tower_tucohy          53          16         0.6        0.75       0.713       0.543
        tower_wooden          53          46       0.824       0.304       0.283       0.187
```

## Test data mAP
```
         Class              Images     Targets       P           R         mAP@.5      mAP@.5:.95
                 all         123         202       0.825       0.643       0.618       0.471
       tower_lattice         123          88       0.887       0.807        0.79        0.64
        tower_tucohy         123          45       0.705       0.689       0.652       0.541
        tower_wooden         123          69       0.882       0.435       0.411       0.232
```

## Inference on the images look like following images
<img src = "https://raw.githubusercontent.com/yushendye/Aerial-Image-Detection/main/105_4350.jpg"> <br>
<img src = "https://raw.githubusercontent.com/yushendye/Aerial-Image-Detection/main/19_00137.jpg"> <br>
<img src = "https://raw.githubusercontent.com/yushendye/Aerial-Image-Detection/main/25_00029.jpg"> <br>
<img src = "https://raw.githubusercontent.com/yushendye/Aerial-Image-Detection/main/34_1005.jpg "> <br>
<img src = "https://raw.githubusercontent.com/yushendye/Aerial-Image-Detection/main/67_02716.jpg "> <br>
