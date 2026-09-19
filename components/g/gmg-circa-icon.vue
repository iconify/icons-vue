<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pvkrtue5x"/><path class="zq3nj2z8m"/><path class="ioyqd3avt"/><path class="g4o8tyoli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gmg-circa-icon" /></template>
<style>
.g4o8tyoli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.742 33.115h6.897c-5.057 6.97-14.831 8.542-21.832 3.51c-7-5.031-8.576-14.76-3.519-21.731c5.057-6.97 14.83-8.542 21.831-3.51a15.6 15.6 0 0 1 3.52 3.502h-6.897");
}

.ioyqd3avt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 13.245c5.935 0 10.755 4.82 10.755 10.755S29.935 34.755 24 34.755S13.245 29.935 13.245 24S18.065 13.245 24 13.245");
}

.pvkrtue5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5c11.88 0 21.5 9.62 21.5 21.5S35.88 45.5 24 45.5S2.5 35.88 2.5 24S12.12 2.5 24 2.5");
}

.zq3nj2z8m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 18.511c3.038 0 5.489 2.45 5.489 5.489s-2.45 5.489-5.489 5.489s-5.489-2.45-5.489-5.489s2.45-5.489 5.489-5.489");
}

</style>
