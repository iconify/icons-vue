<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="cg45gs_bk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cursed-house-multiplayer-gmm" /></template>
<style>
.cg45gs_bk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.958 29.455V18.533l3.271 10.934L35.5 18.549v10.918m-15.84-.012V18.533l3.27 10.934l3.271-10.918v10.918m-9.12-8.644a2.29 2.29 0 0 0-4.581 0v6.354a2.29 2.29 0 0 0 4.581 0v-1.81h-2.29");
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
