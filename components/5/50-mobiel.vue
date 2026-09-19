<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="csd0bg0ao"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:50-mobiel" /></template>
<style>
.csd0bg0ao {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.076 24H38.5m-3.712-3.712v7.424m-3.712-1.206a4.92 4.92 0 0 1-4.918 4.918h0a4.92 4.92 0 0 1-4.918-4.918v-5.011a4.92 4.92 0 0 1 4.918-4.919h0a4.92 4.92 0 0 1 4.918 4.919M9.5 30.171c1.025.86 2.02 1.253 4.505 1.253h.427a4.16 4.16 0 0 0 4.162-4.163h0a4.16 4.16 0 0 0-4.162-4.162H9.5v-6.523h9.094");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
