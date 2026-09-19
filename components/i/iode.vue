<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="botpbwbja"/><path class="zq4h6qbst"/><circle class="j1hcn9s3j"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iode" /></template>
<style>
.botpbwbja {
  cx: 12.237px;
  cy: 14.997px;
  r: 0.75px;
  fill: currentColor;
}

.j1hcn9s3j {
  cx: 28.883px;
  cy: 26.123px;
  r: 7.63px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
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

.zq4h6qbst {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.237 19.372V33.68");
}

</style>
