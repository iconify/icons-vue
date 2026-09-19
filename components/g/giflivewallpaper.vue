<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="bt2afop1a"/><path class="g8u0tcnze"/><circle class="di0eyabgz"/><path class="h9637bb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:giflivewallpaper" /></template>
<style>
.bt2afop1a {
  width: 21.63px;
  height: 39px;
  x: 13.18px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.8px;
}

.di0eyabgz {
  cx: 18.84px;
  cy: 6.99px;
  r: 0.71px;
  fill: currentColor;
}

.g8u0tcnze {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.18 9.42h21.64M13.18 38.31h21.64M21.17 6.99h5.66");
}

.h9637bb-z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.72 19.82v8.36m-2.63-5.56a2.8 2.8 0 0 0-2.94-2.8a2.91 2.91 0 0 0-2.65 3v2.6a2.8 2.8 0 0 0 2.8 2.8h0a2.79 2.79 0 0 0 2.79-2.8H19.3m8.02-5.6h4.18M27.32 24h2.72m-2.72-4.18v8.36");
}

</style>
