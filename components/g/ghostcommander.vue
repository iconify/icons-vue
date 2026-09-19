<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="jy9rgje8r"/><path class="l8gi0xbja"/><path class="hinwbwbgz"/><path class="kt1wxebrq"/><path class="k50025blf"/><circle class="q15mj6b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ghostcommander" /></template>
<style>
.hinwbwbgz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.75 18.471c1.06-1.19 2.916-.543 4.991 1.783c1.746 2.108 3.427 3.11 5.53 4.464c-2.74 1.492-5.41.687-8.038-.628c-2.289-1.299-4.268-3.594-2.483-5.619");
}

.jy9rgje8r {
  cx: 19.453px;
  cy: 10.726px;
  r: 0.75px;
  fill: currentColor;
}

.k50025blf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.444 19.87c4.075-2.817 7.225-.04 7.287.04m-15.996-4.614l20.54-.11");
}

.kt1wxebrq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.253 24.684c6.965 2.042 13.488-.698 12.607-5.555c-.949-4.06-5.082.027-6.109.886c.525 2.163-.195 4.821-3.865 3.047c-1.25-2.037-2.714-3.066-4.939-3.72c-1.48-.594-2.255.372-3.293.753");
}

.l8gi0xbja {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.496 17.98v-.61c0-4.02 2.25-7.52 5.56-9.3c1.48-.8 3.18-1.25 4.99-1.25c1.77 0 3.43.43 4.89 1.2c3.37 1.76 5.66 5.29 5.66 9.35v.05m0 5.7v10.37c0 1.1-.9 2-2 2l-1.82.01v5.22a2.81 2.81 0 0 1-2.79 2.78c-.76 0-1.46-.32-1.96-.82s-.82-1.2-.82-1.96V35.5h-2.32v5.22a2.8 2.8 0 0 1-2.78 2.78c-.76 0-1.46-.32-1.96-.82c-.51-.5-.82-1.2-.83-1.96l-.01-5.23h-1.81c-1.1 0-2-.9-2-2V22.83m3.64-18.33l1.92 3.57m11.9-3.57l-2.02 3.52");
}

.q15mj6b9o {
  cx: 28.428px;
  cy: 10.723px;
  r: 0.75px;
  fill: currentColor;
}

</style>
