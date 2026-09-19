<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="aonj5ccbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chalo" /></template>
<style>
.aonj5ccbu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.506 25.868c0 1.511 1.209 2.72 2.62 2.72a2.71 2.71 0 0 0 2.72-2.72v-2.72c0-1.51-1.21-2.72-2.72-2.72s-2.62 1.21-2.62 2.72zm-5.369-5.339v8.059h4.029m-5.369 0l-2.619-8.059l-2.72 8.059m.907-2.72h3.526M14.78 20.529v8.059m5.339-8.059v8.059m-5.339-4.029h5.339m-6.679 1.309a2.71 2.71 0 0 1-2.72 2.72h0A2.71 2.71 0 0 1 8 25.868v-2.72a2.71 2.71 0 0 1 2.72-2.72h0c1.511 0 2.62 1.21 2.62 2.72h0m24.645-3.736H40v2.015");
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
