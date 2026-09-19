<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mlusc1b8j"/><circle class="cs-nnzbrr"/><path class="j-ay36g0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:knockonports" /></template>
<style>
.cs-nnzbrr {
  cx: 24px;
  cy: 38.74px;
  r: 5.83px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j-ay36g0z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.8 38.22A14.28 14.28 0 0 0 34.05 15M14 15a14.28 14.28 0 0 0 4.2 23.22");
}

.mlusc1b8j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.06 5.57h25.88a.83.83 0 0 1 .66 1.33L29.29 18a.84.84 0 0 1-.67.33h-9.24a.81.81 0 0 1-.66-.33L10.4 6.9a.83.83 0 0 1 .66-1.33");
}

</style>
