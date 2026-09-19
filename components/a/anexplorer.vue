<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uhde9gb5x"/><path class="hrll78j7d"/><rect class="u361022sv"/><path class="w83m95b5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:anexplorer" /></template>
<style>
.hrll78j7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 18.28h-39V37a2.18 2.18 0 0 0 2.17 2.2h34.65A2.18 2.18 0 0 0 43.5 37h0Z");
}

.u361022sv {
  width: 9.94px;
  height: 14.3px;
  x: 30.34px;
  y: 21.71px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.5px;
}

.uhde9gb5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.68 13H24.77c-2-.1-5.93-4.23-8.19-4.23h-9.9A2.18 2.18 0 0 0 4.5 11h0v7.29h39v-3.42A1.83 1.83 0 0 0 41.68 13");
}

.w83m95b5j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.34 24.45h9.95m-9.95 8.58h9.95");
}

</style>
