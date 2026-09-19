<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="dd8ot2b6h"/><ellipse class="j-4_fbbjd"/><path class="kj5is1bej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:c6-yellow" /></template>
<style>
.dd8ot2b6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.737 26.633v.066c0 2.926-2.322 5.297-5.186 5.297s-5.186-2.371-5.186-5.297V21.3c0-2.926 2.322-5.298 5.186-5.298s5.186 2.372 5.186 5.298v.066");
}

.j-4_fbbjd {
  cx: 31.448px;
  cy: 26.699px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.186px;
  ry: 5.298px;
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

.kj5is1bej {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.184 17.954c-.864-1.156-2.181-1.95-4.363-1.95h-.365c-2.864 0-5.185 2.371-5.185 5.297V26.7");
}

</style>
