<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ur1md-bly"/><rect transform="matrix(-1 0 0 -1 30.069 46)" class="urp3_tbgm"/><path class="iln9f0byr"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gsc-everywhere" /></template>
<style>
.iln9f0byr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.326 26.893c.645.542 1.342.79 2.907.79h.793a2.34 2.34 0 0 0 2.336-2.341h0A2.34 2.34 0 0 0 25.026 23H23.44a2.34 2.34 0 0 1-2.337-2.341h0a2.34 2.34 0 0 1 2.337-2.342h.793c1.564 0 2.261.248 2.906.79m9.361 6.796a3.53 3.53 0 0 1-3.069 1.78h0a3.534 3.534 0 0 1-3.534-3.534V21.85a3.534 3.534 0 0 1 3.534-3.534h0c1.311 0 2.455.714 3.066 1.774");
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

.ur1md-bly {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.569 18.317V28.92a3.534 3.534 0 0 1-3.535 3.534h0a3.52 3.52 0 0 1-2.499-1.035");
}

.urp3_tbgm {
  width: 7.069px;
  height: 9.366px;
  x: 11.5px;
  y: 18.317px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.534px;
  ry: 3.534px;
}

</style>
