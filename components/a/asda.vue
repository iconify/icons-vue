<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="nkdtshbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:asda" /></template>
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

.nkdtshbcs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.19 27.838c.603.785 1.359 1.077 2.41 1.077h1.456c1.354 0 2.452-1.098 2.452-2.458S22.41 24 21.056 24H19.45a2.455 2.455 0 0 1-2.455-2.457a2.46 2.46 0 0 1 2.46-2.458h1.448c1.052 0 1.808.292 2.41 1.077m1.793 8.753v-9.83h2.212a4.3 4.3 0 0 1 4.3 4.3v1.23a4.3 4.3 0 0 1-4.3 4.3zm-10.172-3.256h-4.355M9.5 28.915l3.256-9.83l3.257 9.83m21.408-3.256h-4.355m-1.079 3.256l3.256-9.83l3.257 9.83");
}

</style>
