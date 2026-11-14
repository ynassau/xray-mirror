# X-Ray Mirror

A browser page that overlays a 3D skull, brain, muscles and hand bones on your live camera picture.

This copy is based on the X-Ray Mirror page published at https://masterofvfx2070.github.io/xray-mirror/, with these changes:

- **Auto-fit face shape**: learns the width/height balance of your face and stretches the model to match (the original only scaled it evenly).
- **Camera angle**: automatic setting for phone selfie cameras (about 72° upright, 46° sideways), plus a manual slider. The original assumed 63° for every camera.
- **Talking and smiling**: the chin and mouth corners barely affect the fit, so the skull no longer grows when you open your mouth.
- **Turning the phone**: the picture's shape updates when the camera's orientation changes.
- Tracking data now shows the camera angle, learned face shape and fit error.

Anatomy models: BodyParts3D, © The Database Center for Life Science, licensed under CC Attribution-Share Alike 2.1 Japan.

It is not a scan of you and not a medical tool. Video is processed on your device and never uploaded.
