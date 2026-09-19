<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="hf4a2ubmv"/><path class="s59r8i2qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ar-card" /></template>
<style>
.hf4a2ubmv {
  width: 39px;
  height: 26.897px;
  x: 4.5px;
  y: 10.552px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.017px;
  ry: 2.017px;
}

.s59r8i2qh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.88 27.362h13.448M9.879 32.07h29.587");
}

</style>
