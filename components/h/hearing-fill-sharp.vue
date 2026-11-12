<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3xpich_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hearing-fill-sharp" /></template>
<style>
.h3xpich_h {
  fill: currentColor;
  d: path("M2 9a7 7 0 1 1 14 0c0 1.529-.372 3.012-1.326 4.23c-.71.906-1.629 1.536-2.582 2.155c-.533.347-1.147.724-1.571 1.203c-.364.411-.521.864-.521 1.412a3.98 3.98 0 0 1-1.172 2.828A3.998 3.998 0 0 1 2 18Zm19.155-2.898c.297.937.448 1.915.447 2.898a9.6 9.6 0 0 1-.447 2.898a9.5 9.5 0 0 1-1.341 2.683a1 1 0 1 1-1.628-1.162a7.5 7.5 0 0 0 1.062-2.124A7.5 7.5 0 0 0 19.602 9a7.5 7.5 0 0 0-.354-2.295a7.5 7.5 0 0 0-1.062-2.124a1 1 0 0 1 .233-1.395a1 1 0 0 1 1.395.233a9.5 9.5 0 0 1 1.341 2.683M8.269 8.318a1 1 0 0 1 1.097-.248c.383.15.634.519.634.93a1 1 0 0 0 2 0a3 3 0 1 0-6 0a.997.997 0 0 0 1 1c.324 0 .5.175.5.5s-.176.5-.5.5a1 1 0 0 0 0 2c.363 0 .724-.067 1.057-.213c1.21-.53 1.724-1.956 1.291-3.173a2.4 2.4 0 0 0-1.079-1.296");
}

</style>
