<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="mkmj--b1p"/><rect class="mx3x_ybrr"/><rect class="bqaz64blh"/><rect class="zi0b4_ghl"/><path class="ylrjw1k9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hieduscientificcalculator" /></template>
<style>
.bqaz64blh {
  width: 16.55px;
  height: 16.55px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.mkmj--b1p {
  width: 16.55px;
  height: 16.55px;
  x: 25.95px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.mx3x_ybrr {
  width: 16.55px;
  height: 16.55px;
  x: 5.5px;
  y: 25.95px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.ylrjw1k9w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.87 31.3h10.71m-10.71 5.84h10.71M8.06 14.22h1.91l1.57 4.27l2.13-9.42h5.82m9.8 0h9.87m-8.9 9.42c2.15-3.76 1.84-5.75 1.84-9.42m4.39 0v9.42M15.3 38.51h4.29M15.3 31.1l2.15-1.17m0 0v8.58m-9.49-4.29h4.29");
}

.zi0b4_ghl {
  width: 16.55px;
  height: 16.55px;
  x: 25.95px;
  y: 25.95px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
