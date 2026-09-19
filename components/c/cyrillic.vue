<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s601tvv7e"/><circle class="t26n92ubx"/><path class="gbml88bhq"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cyrillic" /></template>
<style>
.gbml88bhq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.396 23.56a2 2 0 0 1 2-2h0a2 2 0 0 1 2 2v1.3a2 2 0 0 1-2 2h0a2 2 0 0 1-2-2M25.5 18.925l-3 10.15");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.s601tvv7e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.265 26.875v-8l5.3 8v-8m13.531-.015v8m5.3-8v8m-5.3-4.015h5.3m-15.666-1.27v6c0 1.105-.886 2-1.98 2h0q-.342-.001-.648-.11");
}

.t26n92ubx {
  cx: 18.731px;
  cy: 19.175px;
  r: 0.75px;
  fill: currentColor;
}

</style>
