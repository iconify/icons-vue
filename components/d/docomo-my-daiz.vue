<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="a8lvlr1gr"/><circle class="q53zp6k1d"/><path class="d_payi6tx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:docomo-my-daiz" /></template>
<style>
.a8lvlr1gr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.015 14.815a2 2 0 1 1 4 0v3.3m-4-5.3v5.3m4-3.3a2 2 0 1 1 4 0v3.3m6.307 9.279h5.858l-5.858 7.792h5.858");
}

.d_payi6tx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.393 27.394v7.791m-2.929-2.94c0 1.624-1.311 2.94-2.929 2.94s-2.929-1.316-2.929-2.94v-1.911c0-1.624 1.311-2.94 2.93-2.94s2.928 1.316 2.928 2.94m0 4.851v-7.791m-8.786 2.94c0-1.624-1.311-2.94-2.929-2.94s-2.929 1.316-2.929 2.94v1.911c0 1.624 1.311 2.94 2.93 2.94s2.928-1.316 2.928-2.94m0 2.74V23.224m12.437-5.109l-2.13-5.3m4 0l-2.54 7.2a1.2 1.2 0 0 1-1.131.8h-.329");
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

.q53zp6k1d {
  cx: 28.393px;
  cy: 23.792px;
  r: 0.75px;
  fill: currentColor;
}

</style>
