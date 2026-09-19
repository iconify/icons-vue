<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="xc9c6sd3y"/><circle class="vscmc-0hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gls" /></template>
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

.vscmc-0hj {
  cx: 39.034px;
  cy: 29.919px;
  r: 0.75px;
  fill: currentColor;
}

.xc9c6sd3y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.71 17.33v12.734h6.63m2.713-1.237a3.72 3.72 0 0 0 3.14 1.431h1.885a3.182 3.182 0 0 0 0-6.363h-2.041a3.182 3.182 0 0 1 0-6.363h1.884a3.35 3.35 0 0 1 3.14 1.431m-20.523 2.741a4.28 4.28 0 0 0-4.397-4.296a4.46 4.46 0 0 0-3.925 4.454v3.978a4.24 4.24 0 1 0 8.479 0h-4.24");
}

</style>
