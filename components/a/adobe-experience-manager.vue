<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="glkfk8bhf"/><path class="vrtbnabls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adobe-experience-manager" /></template>
<style>
.glkfk8bhf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.75 19.5za4.25 4.25 0 0 1-4.25-4.25A4.25 4.25 0 0 0 24.25 11h-.5a4.25 4.25 0 0 0-4.25 4.25a4.25 4.25 0 0 1-4.25 4.25A4.25 4.25 0 0 0 11 23.75v.5a4.25 4.25 0 0 0 4.25 4.25a4.25 4.25 0 0 1 4.25 4.25A4.25 4.25 0 0 0 23.75 37h.5a4.25 4.25 0 0 0 4.25-4.25a4.25 4.25 0 0 1 4.25-4.25A4.25 4.25 0 0 0 37 24.25v-.5a4.25 4.25 0 0 0-4.25-4.25");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.vrtbnabls {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.37 27.005za4.25 4.25 0 0 1 0-6.01a4.25 4.25 0 0 0 0-6.01l-.354-.354a4.25 4.25 0 0 0-6.01 0a4.25 4.25 0 0 1-6.011 0a4.25 4.25 0 0 0-6.01 0l-.354.353a4.25 4.25 0 0 0 0 6.01a4.25 4.25 0 0 1 0 6.011a4.25 4.25 0 0 0 0 6.01l.353.354a4.25 4.25 0 0 0 6.01 0a4.25 4.25 0 0 1 6.011 0a4.25 4.25 0 0 0 6.01 0l.354-.353a4.25 4.25 0 0 0 0-6.01");
}

</style>
