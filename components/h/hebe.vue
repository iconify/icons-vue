<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sf-gi_zjm"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hebe" /></template>
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

.sf-gi_zjm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 18.329V29.67m0-4.678a2.836 2.836 0 0 1 5.672 0v4.68m7.314-1.347a2.668 2.668 0 0 1-4.987-1.322v-1.735a2.669 2.669 0 0 1 5.337 0v.867H17.5m20.65 2.19a2.668 2.668 0 0 1-4.987-1.322v-1.735a2.669 2.669 0 0 1 5.337 0v.867h-5.337m-7.927-1.024a2.764 2.764 0 0 1 5.527 0v1.796a2.764 2.764 0 1 1-5.527 0m0 2.765V18.617");
}

</style>
