<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="h3hwekbjo"/><circle class="jcd40wb2d"/><path class="zsr_u1b8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-gallery-go-alt" /></template>
<style>
.h3hwekbjo {
  width: 37px;
  height: 30px;
  x: 5.5px;
  y: 9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.jcd40wb2d {
  cx: 31px;
  cy: 20px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zsr_u1b8o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.9 39c0-9.61-7.79-17.4-17.4-17.4");
}

</style>
