<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y92oes3fe"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hh" /></template>
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

.y92oes3fe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.625 16.5v15m0-6.187a3.75 3.75 0 0 1 3.75-3.75h0a3.75 3.75 0 0 1 3.75 3.75V31.5m3.75-15v15m0-6.187a3.75 3.75 0 0 1 3.75-3.75h0a3.75 3.75 0 0 1 3.75 3.75V31.5");
}

</style>
