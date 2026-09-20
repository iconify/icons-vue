<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="egd59tb2y"/><path class="f3k-27b9j"/><circle class="xptte0rbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:filmsim-recipes" /></template>
<style>
.egd59tb2y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5c11.876 0 21.5 9.624 21.5 21.5S35.876 45.5 24 45.5S2.5 35.876 2.5 24S12.124 2.5 24 2.5");
}

.f3k-27b9j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.536 29.018V18.982h3.286c1.857 0 3.363 1.51 3.363 3.37s-1.506 3.371-3.363 3.371h-3.286m3.286 0l3.285 3.292m-15.689-1.097c.616.801 1.387 1.1 2.461 1.1h1.486a2.503 2.503 0 0 0 2.503-2.504v-.01A2.503 2.503 0 0 0 21.365 24h-1.64a2.506 2.506 0 0 1-2.505-2.506a2.51 2.51 0 0 1 2.511-2.512h1.478c1.073 0 1.845.299 2.46 1.1M10.074 24h3.262m-3.262 5.018V18.982h5.018");
}

.xptte0rbv {
  cx: 36.502px;
  cy: 27.594px;
  r: 1.424px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
