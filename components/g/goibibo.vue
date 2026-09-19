<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x0i496bnx"/><rect transform="matrix(-1 0 0 -1 20.707 48.417)" class="si2cv1eta"/><rect class="cvfs8kbvf"/><rect class="u7qx7wbrk"/><circle class="v9sgo5bpx"/><path class="ceilrbcdb"/><circle class="hc3qz7b8x"/><path class="d8kd7fbkr"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:goibibo" /></template>
<style>
.ceilrbcdb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.225 21.752v4.913");
}

.cvfs8kbvf {
  width: 3.707px;
  height: 4.912px;
  x: 14.39px;
  y: 21.752px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.854px;
  ry: 1.854px;
}

.d8kd7fbkr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.947 21.752v4.913m-5.652-3.059c0-1.024.83-1.854 1.853-1.854h0c1.024 0 1.854.83 1.854 1.854v1.205c0 1.024-.83 1.854-1.854 1.854h0a1.854 1.854 0 0 1-1.854-1.854m0 1.854V19.25m7.773 4.356c0-1.024.83-1.854 1.854-1.854h0c1.024 0 1.854.83 1.854 1.854v1.205c0 1.024-.83 1.854-1.854 1.854h0a1.854 1.854 0 0 1-1.854-1.854m0 1.854V19.25");
}

.hc3qz7b8x {
  cx: 27.947px;
  cy: 19.482px;
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

.si2cv1eta {
  width: 3.707px;
  height: 4.912px;
  x: 8.5px;
  y: 21.752px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.854px;
  ry: 1.854px;
}

.u7qx7wbrk {
  width: 3.707px;
  height: 4.912px;
  x: 35.793px;
  y: 21.752px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.854px;
  ry: 1.854px;
}

.v9sgo5bpx {
  cx: 20.225px;
  cy: 19.482px;
  r: 0.75px;
  fill: currentColor;
}

.x0i496bnx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.207 21.752v5.562c0 1.023-.83 1.853-1.853 1.853h0c-.512 0-.976-.207-1.311-.543");
}

</style>
