<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="hamlhzrfg"/><path class="ar9icn-6t"/><rect class="u-6k40fzf"/><path class="j4qwfiwxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:luxchat4gov" /></template>
<style>
.ar9icn-6t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.5 42.5a4 4 0 0 0 0-8h-13a4 4 0 0 1-4-4v-21a4 4 0 0 0-4-4m22 15.832l-1.768 5.336l-1.768-5.336");
}

.hamlhzrfg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.5 17.5a4 4 0 0 1 4-4h13a4 4 0 0 1 4 4v21");
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

.j4qwfiwxb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.036 23.1a1.768 1.768 0 1 0-3.536 0v1.8a1.768 1.768 0 1 0 3.536 0h-1.768");
}

.u-6k40fzf {
  width: 3.536px;
  height: 5.337px;
  x: 22.444px;
  y: 21.332px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.768px;
  ry: 1.768px;
}

</style>
