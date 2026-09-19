<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="h3h45xz-y"/><path class="feo9aab1x"/><path class="ywgp5zb9r"/><path class="b0pklzhcb"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:giant-eagle" /></template>
<style>
.b0pklzhcb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.415 30.72c1.1 0 2 .9 2 2v1.3c0 1.1-.9 2-2 2h0c-1.1 0-2-.9-2-2v-1.3c0-1.1.9-2 2-2m4.694-2.693v7a.94.94 0 0 0 1 1h.3m-10.591-2c0 1.1-.9 2-2 2h0c-1.1 0-2-.9-2-2v-1.3c0-1.1.9-2 2-2h0c1.1 0 2 .9 2 2m0 3.3v-5.4m16.357 4.4c-.3.6-1 1-1.7 1h0c-1.1 0-2-.9-2-2v-1.3c0-1.1.9-2 2-2h0c1.1 0 2 .9 2 2v.7h-4m-19.25 1.6c-.3.6-1 1-1.7 1h0c-1.1 0-2-.9-2-2v-1.3c0-1.1.9-2 2-2h0c1.1 0 2 .9 2 2v.7h-4M8.49 14.279h9.97m11 0h10.03M18.981 9.807s-.093 5.855 5.078 5.596c1.018-4.835-5.078-5.596-5.078-5.596m5.078 5.596c2.151.008 3.394-.898 4.281-2.521c.621-1.515.862-3.053.497-4.628c-.014.003-4.414.377-5.077 4.355");
}

.feo9aab1x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.327 20.504v6c0 1.1-.9 2-2 2h0c-.6 0-1.1-.2-1.4-.6");
}

.h3h45xz-y {
  cx: 18.192px;
  cy: 17.915px;
  r: 0.75px;
  fill: currentColor;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.ywgp5zb9r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.327 20.404c1.1 0 2 .9 2 2v1.3c0 1.1-.9 2-2 2h0c-1.1 0-2-.9-2-2v-1.3c0-1.1.9-2 2-2m4.865-.087v5.4m17.182-7.002v6a.94.94 0 0 0 1 1h.3m-2.401-5.4h2.201m-11.657 3.402c0 1.1-.9 2-2 2h0c-1.1 0-2-.9-2-2v-1.3c0-1.1.9-2 2-2h0c1.1 0 2 .9 2 2m0 3.3v-5.4m7.119 5.4v-3.3c0-1.1-.9-2-2-2h0c-1.1 0-2 .9-2 2m0 3.3v-5.4m-.521 10.503v6c0 1.1-.9 2-2 2h0c-.6 0-1.1-.2-1.4-.6");
}

</style>
