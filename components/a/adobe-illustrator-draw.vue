<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="t_gxs2b6b"/><path class="nej-vbbqg"/><circle class="k5uu38b1f"/><path class="aynlu4mmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adobe-illustrator-draw" /></template>
<style>
.aynlu4mmy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 28.175v-5.291");
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

.k5uu38b1f {
  cx: 24px;
  cy: 21.093px;
  r: 1.791px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nej-vbbqg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.773 13.066c0 2.495-1.71 4.793-3.688 6.468l5.06 9.586l.855-.945l.855.945l5.06-9.586c-1.977-1.675-3.688-3.973-3.688-6.468z");
}

.t_gxs2b6b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11 13.066l13 21.868l13-21.868");
}

</style>
