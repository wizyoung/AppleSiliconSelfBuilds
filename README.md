# AppleSiliconSelfBuilds

### 1. Python3 packages:

NOTE: I'm using Python3.9 which is installed by conda-forge, and I also installed the arm64 numpy by conda-forge.

1. (20201217) pytorch: [torch-1.8.0a0-cp39-cp39-macosx_11_0_arm64.whl](./builds/torch-1.8.0a0-cp39-cp39-macosx_11_0_arm64.whl)

   NOTE: Currently not using OpenMP in building due to deps errors. Building details refer to [thread](https://github.com/pytorch/pytorch/issues/48145#issuecomment-747631341).
   
2. (20201218) opencv-python: [opencv_contrib_python-4.5.0+bbaa777-cp39-cp39-macosx_11_0_arm64.whl](./builds/opencv_contrib_python-4.5.0+bbaa777-cp39-cp39-macosx_11_0_arm64.whl)

   NOTE: opencv-contrib is also packed into the opencv-python wheel
   file.
   
3. (20220420) decord: 

   [decord-0.6.0-cp39-cp39-macosx_12_0_arm64.whl](./builds/decord-0.6.0-cp39-cp39-macosx_12_0_arm64.whl)
   
   NOTE: You must use brew to install ffmpeg4 to use decord: `brew install ffmpeg@4` and make sure ffmpeg4 is installed at location `/opt/homebrew/opt/ffmpeg@4`

### 2. VSCODE Extensions

1. Now officially supported ~~(20201220) vscode-cpptools: [cpptools-1.1.3.vsix](./builds/cpptools-1.1.3.vsix)~~

   
