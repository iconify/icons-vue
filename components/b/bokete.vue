<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="mkzs0kbvh"/><path class="pxst2x1sj"/><circle class="jv64roogq"/><circle class="oj75-41jl"/><path class="w6dcqubun"/><ellipse class="n1gz2hbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bokete" /></template>
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

.jv64roogq {
  cx: 14.5px;
  cy: 14px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mkzs0kbvh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.195 26.998A3.5 3.5 0 0 1 20.5 24a3.5 3.5 0 0 1 3.5-3.5a3.5 3.5 0 0 1 3.5 3.5a3.5 3.5 0 0 1-1.684 2.992");
}

.n1gz2hbcv {
  cx: 24px;
  cy: 35.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.5px;
  ry: 3.5px;
}

.oj75-41jl {
  cx: 33.5px;
  cy: 14px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pxst2x1sj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.724 29.842A6.75 4.75 0 0 1 17 30a6.75 4.75 0 0 1-6.75-4.75A6.75 4.75 0 0 1 17 20.5a6.75 4.75 0 0 1 4.417 1.158m5.176-.006A6.75 4.75 0 0 1 31 20.5a6.75 4.75 0 0 1 6.75 4.75A6.75 4.75 0 0 1 31 30a6.75 4.75 0 0 1-1.724-.158");
}

.w6dcqubun {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.404 33.335A5.5 4.25 0 0 1 18.5 31a5.5 4.25 0 0 1 5.5-4.25A5.5 4.25 0 0 1 29.5 31a5.5 4.25 0 0 1-.9 2.329");
}

</style>
