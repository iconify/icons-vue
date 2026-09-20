<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="nqoasmbyp"/><circle class="ulgp7lr-z"/><circle class="r32dt0hof"/><circle class="y85d4_3_l"/><circle class="pn6m1ub2r"/><circle class="e8vjb6bmv"/><circle class="w039job9j"/><circle class="aqm0apfod"/><circle class="px_r9jb3u"/><circle class="y1gyen97a"/><circle class="xo0h-rbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:handpickd" /></template>
<style>
.aqm0apfod {
  cx: 19px;
  cy: 33.314px;
  r: 0.75px;
  fill: currentColor;
}

.e8vjb6bmv {
  cx: 19px;
  cy: 38.314px;
  r: 0.75px;
  fill: currentColor;
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

.nqoasmbyp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.912 24.815l.836-4.95c.5-2.96-2.128-5.46-4.753-5.46s-5.2 2.488-4.753 5.46l.742 4.95m-.79-15.879v9.821");
}

.pn6m1ub2r {
  cx: 24px;
  cy: 38.314px;
  r: 0.75px;
  fill: currentColor;
}

.px_r9jb3u {
  cx: 14px;
  cy: 33.314px;
  r: 0.75px;
  fill: currentColor;
}

.r32dt0hof {
  cx: 29px;
  cy: 33.314px;
  r: 0.75px;
  fill: currentColor;
}

.ulgp7lr-z {
  cx: 24px;
  cy: 28.314px;
  r: 0.75px;
  fill: currentColor;
}

.w039job9j {
  cx: 14px;
  cy: 38.314px;
  r: 0.75px;
  fill: currentColor;
}

.xo0h-rbpv {
  cx: 34px;
  cy: 38.314px;
  r: 0.75px;
  fill: currentColor;
}

.y1gyen97a {
  cx: 29px;
  cy: 38.314px;
  r: 0.75px;
  fill: currentColor;
}

.y85d4_3_l {
  cx: 34px;
  cy: 33.314px;
  r: 0.75px;
  fill: currentColor;
}

</style>
