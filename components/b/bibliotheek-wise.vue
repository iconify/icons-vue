<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u4scffb4c"/><circle class="hbeb8qcsx"/><path class="r7h2r8bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bibliotheek-wise" /></template>
<style>
.hbeb8qcsx {
  cx: 17.682px;
  cy: 24.34px;
  r: 3.776px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r7h2r8bte {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.72 18.646l5.025-5.026a1.326 1.326 0 0 1 1.875 0l5.026 5.026m0 11.389L18.62 35.06a1.326 1.326 0 0 1-1.875 0l-5.026-5.026");
}

.u4scffb4c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.078 17.031c4.35 4.349 4.932 9.494-.469 14.894c-5.4 5.4-21.374 15.576-31.123 5.827S3.808 13.3 8.306 8.802c6.921-6.92 25.858 1.315 32.772 8.23");
}

</style>
