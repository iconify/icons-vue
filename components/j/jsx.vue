<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ylvdo9j9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:jsx" /></template>
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

.ylvdo9j9d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.675 20v6a2 2 0 1 1-4 0v-.664m9.183 1.787c.49.639 1.106.877 1.962.877h1.184A1.996 1.996 0 0 0 26 26.004v-.009A1.996 1.996 0 0 0 24.004 24h-1.307a2 2 0 0 1-1.997-1.997c0-1.106.896-2.002 2.002-2.002h1.178c.856 0 1.47.237 1.961.876M31.025 20l2.65 3l2.65-3m0 8l-2.65-3l-2.65 3");
}

</style>
