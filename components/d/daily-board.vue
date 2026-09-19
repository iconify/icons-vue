<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="r73cxn7qa"/><path class="viwhscc1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:daily-board" /></template>
<style>
.r73cxn7qa {
  width: 39px;
  height: 26.768px;
  x: 4.5px;
  y: 7.97px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.055px;
  ry: 3.055px;
}

.viwhscc1l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.739 34.73v2.908a2.387 2.387 0 0 0 2.393 2.392h15.091a2.387 2.387 0 0 0 2.393-2.392V34.73zm3.091-12.552h7.225m-.01-10.528v10.535");
}

</style>
