<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hki_ddbyx"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aliucordinstaller" /></template>
<style>
.hki_ddbyx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.426 18.003v.053a4.238 4.238 0 0 1-8.476 0v-4.318a4.238 4.238 0 0 1 8.476 0v.052m-18.852 8.466L18.82 9.5m4.07 12.794L18.82 9.5m2.709 8.514h-5.543m2.444 15.208l5.278 5.278l5.278-5.278M23.708 38.5V25.706");
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
