<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(-25 19.826 21.207)" class="g3s3inbcr"/><circle class="yamwi8bmn"/><path class="ga44vac0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cemiuiler" /></template>
<style>
.g3s3inbcr {
  width: 23.746px;
  height: 23.746px;
  x: 7.953px;
  y: 9.334px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.418px;
  ry: 4.418px;
}

.ga44vac0l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.425 18.449A12.149 12.149 0 1 1 21.76 37.56");
}

.yamwi8bmn {
  cx: 37.254px;
  cy: 10.194px;
  r: 2.761px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
