<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="upwc_rbxp"/><path class="elk0xdbnc"/><circle class="bshvmub8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:leafly" /></template>
<style>
.bshvmub8u {
  cx: 37.818px;
  cy: 25.989px;
  r: 0.75px;
  fill: currentColor;
}

.elk0xdbnc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.546 24.591v2.454a1.82 1.82 0 0 1-1.822 1.82h0a1.8 1.8 0 0 1-1.285-.532M9.5 19.134v7.268h3.642");
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

.upwc_rbxp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.444 21.588h2.543m-1.46 4.814v-5.996c0-.703.569-1.272 1.271-1.272h0c.626 0 1.017.186 1.285.533m-10.532 5.821a1.82 1.82 0 0 1-1.58.917h0a1.82 1.82 0 0 1-1.818-1.817v-1.182c0-1.006.815-1.822 1.82-1.822h0a1.82 1.82 0 0 1 1.815 1.822v.59h-3.635m8.779 2.409v-4.814m0 3a1.82 1.82 0 0 1-1.814 1.821h0a1.82 1.82 0 0 1-1.821-1.821v-1.182a1.82 1.82 0 0 1 1.821-1.821h0a1.82 1.82 0 0 1 1.818 1.82m6.584-4.27v6.364c0 .501.405.907.907.907h.275m4.84-4.818v3a1.82 1.82 0 0 1-1.818 1.821h0a1.82 1.82 0 0 1-1.82-1.821v-3");
}

</style>
