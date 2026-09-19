<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="mfloa2bec"/><circle class="vg2fn797s"/><circle class="e58aujqsc"/><circle class="k2yo-1b0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-assistant" /></template>
<style>
.e58aujqsc {
  cx: 39.83px;
  cy: 16.6px;
  r: 2.67px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k2yo-1b0t {
  cx: 32.36px;
  cy: 34.8px;
  r: 5.45px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mfloa2bec {
  cx: 15.57px;
  cy: 17.82px;
  r: 10.07px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vg2fn797s {
  cx: 32.36px;
  cy: 22.27px;
  r: 4.46px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
