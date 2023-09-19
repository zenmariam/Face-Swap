In this project we will use openCV and dlib to swap the faces from two sample images.

The steps involved in the project:
- Download the pre-trained model for shape predictor.
- Creating a function for extracting the index.
- Load the source and destination image from the internet.
- Converting the images into numpy array and then coverting the images into grayscale.
- Load face detector and face landmarks predictor using dlib.
- Perform triangualation on the images to cut out the face.
- Creating empty masks for the imges.
- Swapping the face of the source image onto the destination image.
- Using seamless cone for adjusting color scheme.
