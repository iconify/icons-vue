<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="iok20bc7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cleantech-park-app" /></template>
<style>
.iok20bc7l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 15.096L15.096 5.5M5.5 22.918L22.918 5.5M5.5 30.74L30.74 5.5M5.5 38.562L38.562 5.5m-29.178 37L42.5 9.384M17.206 42.5L42.5 17.206M25.028 42.5L42.5 25.028M32.85 42.5l9.65-9.65");
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

</style>
