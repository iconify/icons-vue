<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d3cf4pbnm"/><circle class="gjt_50whd"/><path class="j0f965-cj"/><circle class="k3zu_abak"/><path class="r7ee_sf8p"/><circle class="mkt4b63mq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bcr-gui" /></template>
<style>
.d3cf4pbnm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.27 12.506a24 24 0 0 1-.882-4.384c-.157-1.482-1.45-2.583-2.939-2.583H8.54c-1.777 0-3.145 1.534-2.989 3.304c1.576 17.829 15.777 32.03 33.606 33.606c1.77.156 3.304-1.207 3.304-2.984v-6.16c0-2.248-1.101-3.536-2.583-3.693a24 24 0 0 1-4.384-.881a4.9 4.9 0 0 0-4.87 1.244l-2.957 2.957a31.27 31.27 0 0 1-12.599-12.6l2.957-2.956a4.9 4.9 0 0 0 1.244-4.87m20.195-2.394h-13");
}

.gjt_50whd {
  cx: 23.464px;
  cy: 10.112px;
  r: 0.75px;
  fill: currentColor;
}

.j0f965-cj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.464 16.657h-13");
}

.k3zu_abak {
  cx: 23.464px;
  cy: 16.657px;
  r: 0.75px;
  fill: currentColor;
}

.mkt4b63mq {
  cx: 23.464px;
  cy: 23.201px;
  r: 0.75px;
  fill: currentColor;
}

.r7ee_sf8p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.464 23.201h-13");
}

</style>
