<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="jc1oydeao"/><path class="xeorbyb1q"/><rect class="g5t13b_ni"/><path class="f29t4xbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gameloot" /></template>
<style>
.f29t4xbpu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.94 21.491V13.5l4 8l4-7.988V21.5m3.283-4h2.6m1.4 4h-4v-8h4M13.08 16.15a2.65 2.65 0 1 0-5.3 0v2.7a2.65 2.65 0 1 0 5.3 0h-2.65m10.352 0h-3.544m-.878 2.65l2.65-8l2.65 8");
}

.g5t13b_ni {
  width: 5.3px;
  height: 8px;
  x: 25.26px;
  y: 26.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.65px;
  ry: 2.65px;
}

.jc1oydeao {
  width: 39px;
  height: 31px;
  x: 4.5px;
  y: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.xeorbyb1q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.32 26.5v8h4m22.06-8h5.3m-2.65 8v-8m-18.24 0za2.65 2.65 0 0 1 2.65 2.65v2.7a2.65 2.65 0 1 1-5.3 0v-2.7a2.65 2.65 0 0 1 2.65-2.65");
}

</style>
