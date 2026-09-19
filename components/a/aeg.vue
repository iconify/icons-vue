<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="pixmi2bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aeg" /></template>
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

.pixmi2bnb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.371 24h4.033m2.153 6.186h-6.186V17.814h6.186m9.943 4.098a4.1 4.1 0 0 0-4.098-4.098h0a4.1 4.1 0 0 0-4.099 4.098v4.176a4.1 4.1 0 0 0 4.099 4.098h0a4.1 4.1 0 0 0 4.098-4.098h-4.098m-16.063 0h-5.481M10.5 30.186l4.098-12.372l4.099 12.372");
}

</style>
