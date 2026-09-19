<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f7smwvbai"/><circle class="vi_nxfq0r"/><path class="wf0kujx-d"/><circle class="q2g53cbkz"/><path class="fv9pvab6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:divergence-kwgt" /></template>
<style>
.f7smwvbai {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.43 43.327A21.4 21.4 0 0 1 24 45.5C12.126 45.5 2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24a21.4 21.4 0 0 1-2.174 9.431");
}

.fv9pvab6z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.811 22.174v9.003m-12.811 0v-13.59h3.058a5.945 5.945 0 0 1 5.945 5.946v1.699a5.945 5.945 0 0 1-5.945 5.945z");
}

.q2g53cbkz {
  cx: 29.811px;
  cy: 18.012px;
  r: 0.75px;
  fill: currentColor;
}

.vi_nxfq0r {
  cx: 38.5px;
  cy: 38.5px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wf0kujx-d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.654 34.492v8.016m3.692 0v-2.053L38.273 38.5l2.073-1.955v-2.053");
}

</style>
