<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qb4e_3yms"/><path class="q7d3_kbri"/><path class="uyxvgnbzk"/><circle class="k_zcqphbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:band" /></template>
<style>
.k_zcqphbo {
  cx: 24px;
  cy: 27.9px;
  r: 7.8px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q7d3_kbri {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.2 14.387A15.602 15.602 0 1 1 8.4 27.9");
}

.qb4e_3yms {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.2 27.9V8.4a3.9 3.9 0 0 0-3.9-3.9a3.9 3.9 0 0 0-3.9 3.9v19.5");
}

.uyxvgnbzk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.2 19.18a11.7 11.7 0 1 1-3.9 8.72V8.4");
}

</style>
