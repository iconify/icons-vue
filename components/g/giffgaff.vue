<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="gl-i-ubmo"/><path class="sedvm8bsa"/><rect transform="matrix(-1 0 0 -1 24.203 38.39)" class="z0e6zqbbn"/><rect transform="matrix(-1 0 0 -1 35.694 58.781)" class="u7dxswbcz"/><path class="l-tied73u"/><path class="u0tniebwx"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:giffgaff" /></template>
<style>
.gl-i-ubmo {
  cx: 17.573px;
  cy: 12.561px;
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

.l-tied73u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.84 32.838v-8.585a1.82 1.82 0 0 1 1.82-1.821h0c.897 0 1.456.265 1.84.762m-7.247 2.75h5.807m-16.612 0v7.804a2.6 2.6 0 0 1-2.601 2.601h0a2.6 2.6 0 0 1-1.84-.762m12.378-5.351a2.6 2.6 0 0 1-2.602 2.601h0a2.6 2.6 0 0 1-2.601-2.601v-1.69a2.6 2.6 0 0 1 2.601-2.602h0a2.6 2.6 0 0 1 2.601 2.601");
}

.sedvm8bsa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.035 22.642v-8.585a1.82 1.82 0 0 1 1.82-1.821h0c.897 0 1.456.265 1.84.762m-7.247 2.75h5.807m-3.396-3.467a3.6 3.6 0 0 0-.59-.045h0a1.82 1.82 0 0 0-1.82 1.821v8.585h-2.876v-6.894h-2.87v7.804a2.6 2.6 0 0 1-2.602 2.602h0a2.6 2.6 0 0 1-1.839-.762");
}

.u0tniebwx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.664 22.477a3.6 3.6 0 0 0-.59-.045h0a1.82 1.82 0 0 0-1.82 1.82v8.586h-2.87v-6.894");
}

.u7dxswbcz {
  width: 5.203px;
  height: 6.894px;
  x: 15.246px;
  y: 25.944px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.601px;
  ry: 2.601px;
}

.z0e6zqbbn {
  width: 5.203px;
  height: 6.894px;
  x: 9.5px;
  y: 15.748px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.601px;
  ry: 2.601px;
}

</style>
