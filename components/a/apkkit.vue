<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uhde9gb5x"/><path class="hrll78j7d"/><path class="gaq7asbsg"/><path class="qoowv0cci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:apkkit" /></template>
<style>
.gaq7asbsg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.46 32.18A1.23 1.23 0 1 1 28.68 31a1.22 1.22 0 0 1-1.22 1.18m7.12 0A1.23 1.23 0 1 1 35.8 31a1.22 1.22 0 0 1-1.22 1.18");
}

.hrll78j7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 18.28h-39V37a2.18 2.18 0 0 0 2.17 2.2h34.65A2.18 2.18 0 0 0 43.5 37h0Z");
}

.qoowv0cci {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31 24.65a8.72 8.72 0 0 1 8.72 8.72v0a1.24 1.24 0 0 1-1.24 1.24h-15a1.24 1.24 0 0 1-1.24-1.24v0A8.72 8.72 0 0 1 31 24.65m-7.52-1.3l2.48 2.91m12.58-2.91l-2.47 2.91");
}

.uhde9gb5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.68 13H24.77c-2-.1-5.93-4.23-8.19-4.23h-9.9A2.18 2.18 0 0 0 4.5 11h0v7.29h39v-3.42A1.83 1.83 0 0 0 41.68 13");
}

</style>
