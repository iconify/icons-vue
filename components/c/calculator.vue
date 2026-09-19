<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f943c9d9b"/><rect class="awgl0f4gj"/><rect class="vihz49nmw"/><path class="zw1295tid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calculator" /></template>
<style>
.awgl0f4gj {
  width: 16.553px;
  height: 16.553px;
  x: 25.947px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.f943c9d9b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.947 25.947a4 4 0 0 0-4 4V38.5a4 4 0 0 0 4 4H38.5a4 4 0 0 0 4-4v-8.553a4 4 0 0 0-4-4zM9.5 5.5a4 4 0 0 0-4 4v8.553a4 4 0 0 0 4 4h8.553a4 4 0 0 0 4-4V9.5a4 4 0 0 0-4-4z");
}

.vihz49nmw {
  width: 16.553px;
  height: 16.553px;
  x: 5.5px;
  y: 25.947px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.zw1295tid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.776 8.421v10.711m-5.355-5.356h10.711m9.736 17.527h10.711m-10.711 5.842h10.711");
}

</style>
