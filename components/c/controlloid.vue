<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="xwvh-qbzr"/><path class="h3729ubiy"/><circle class="q7v9hqb6x"/><path class="a_fo6wboe"/><circle class="hdov4ublx"/><circle class="ymecapy4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:controlloid" /></template>
<style>
.a_fo6wboe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.06 12l.11-.11a15.38 15.38 0 0 1 19.35 0M18.05 16a1 1 0 0 1 .2-.17a9.66 9.66 0 0 1 11.17 0m5 23.64a8.7 8.7 0 0 1-5.78-2.15h-9.59a8.77 8.77 0 1 1-5.78-15.37h21.14A8.79 8.79 0 0 1 35 39.48h-.61Z");
}

.h3729ubiy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.1 28.94h-2.39v-2.37a.5.5 0 0 0-.5-.5h-2.27a.49.49 0 0 0-.49.5v2.37h-2.4a.51.51 0 0 0-.49.5v2.28a.49.49 0 0 0 .49.49h2.4v2.4a.49.49 0 0 0 .49.49h2.23a.49.49 0 0 0 .49-.49v-2.39h2.4a.49.49 0 0 0 .49-.49v-2.28a.5.5 0 0 0-.45-.51");
}

.hdov4ublx {
  cx: 34.42px;
  cy: 27.06px;
  r: 1.96px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q7v9hqb6x {
  cx: 38.16px;
  cy: 30.8px;
  r: 1.96px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xwvh-qbzr {
  cx: 30.67px;
  cy: 30.8px;
  r: 1.96px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ymecapy4t {
  cx: 34.42px;
  cy: 34.55px;
  r: 1.96px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
