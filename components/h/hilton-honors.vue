<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="nwxo6mlqm"/><circle class="oo_d7ybbw"/><path class="psde8bcic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hilton-honors" /></template>
<style>
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

.nwxo6mlqm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.643 20.25v8m5.3-8v8m-5.3-4.015h5.3m13.235 4.015a2 2 0 0 1-2-2v-1.3a2 2 0 1 1 4 0v1.3a2 2 0 0 1-2 2");
}

.oo_d7ybbw {
  cx: 18.32px;
  cy: 20.5px;
  r: 0.75px;
  fill: currentColor;
}

.psde8bcic {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.32 22.95v5.3m5.962-6.95v6.95m-1.05-5.3h2.099m-4.63-2.7v7a1 1 0 0 0 1 1h.3m15.356 0v-3.3a2 2 0 1 0-4 0m0 3.3v-5.3");
}

</style>
