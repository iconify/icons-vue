<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="aksyo68gn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:585" /></template>
<style>
.aksyo68gn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.913 24a3.049 3.049 0 1 0 0 6.098h1.982a3.049 3.049 0 1 0 0-6.098m0 0a3.049 3.049 0 1 0 0-6.098h-1.982a3.049 3.049 0 1 0 0 6.098m0 0h1.982M9.5 29.07c.842.704 1.659 1.028 3.7 1.028h.35a3.419 3.419 0 1 0 0-6.838H9.5v-5.358h7.47M31.03 29.07c.842.704 1.659 1.028 3.7 1.028h.351a3.419 3.419 0 1 0 0-6.838h-4.05v-5.358H38.5");
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
