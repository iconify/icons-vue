<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="z259k73vn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ccc" /></template>
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

.z259k73vn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.1 25.64v.041a3.3 3.3 0 0 1-3.3 3.3h0a3.3 3.3 0 0 1-3.3-3.3V22.32a3.3 3.3 0 0 1 3.3-3.3h0a3.3 3.3 0 0 1 3.3 3.3v.04m9.2 3.28v.041a3.3 3.3 0 0 1-3.3 3.3h0a3.3 3.3 0 0 1-3.3-3.3V22.32a3.3 3.3 0 0 1 3.3-3.3h0a3.3 3.3 0 0 1 3.3 3.3v.04m9.2 3.28v.041a3.3 3.3 0 0 1-3.3 3.3h0a3.3 3.3 0 0 1-3.3-3.3V22.32a3.3 3.3 0 0 1 3.3-3.3h0a3.3 3.3 0 0 1 3.3 3.3v.04");
}

</style>
