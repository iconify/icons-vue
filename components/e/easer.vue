<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="mvxsigbxw"/><circle class="jhm_td60w"/><circle class="uwj6o3bhk"/><circle class="rl1jviiit"/><path class="n8124byrh"/><path class="z0t-y4bbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:easer" /></template>
<style>
.jhm_td60w {
  cx: 15.87px;
  cy: 38.05px;
  r: 1.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mvxsigbxw {
  cx: 15.87px;
  cy: 27.74px;
  r: 1.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n8124byrh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.81 17.35c-2.11 0-9.81-1.46-9.81-8.18s5.63-6.36 9.55-6.36s9.56-.37 9.56 6.36s-7.7 8.18-9.81 8.18Zm-.26 0c0 1.6 5 4.21 7.27 8.39c4.64 8.53-9.06 14.47-10.58 16.07");
}

.rl1jviiit {
  cx: 19.84px;
  cy: 43.21px;
  r: 1.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uwj6o3bhk {
  cx: 18.91px;
  cy: 32.9px;
  r: 1.98px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z0t-y4bbk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.83 37.76c2.49-.52 10.22-5.59 13.11-13.4m-10.56 7.2A16.23 16.23 0 0 0 27.77 21M17.6 26.77c2.49-.52 6.17-3.29 7-9.42M21.16 6.52h6.79m-6.79 6.87h6.79m6.16-3.84h-4.44m-10.23 0H15");
}

</style>
