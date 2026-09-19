<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cu1512ykr"/><path class="pkpaaxb-j"/><rect class="dy471lbcn"/><rect class="itc0xbcyi"/><rect class="r4qmnofrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:filmic-pro" /></template>
<style>
.cu1512ykr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.63 14.63H42.5V9.5a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h5.13z");
}

.dy471lbcn {
  width: 4.752px;
  height: 6.252px;
  x: 37.748px;
  y: 18.626px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

.itc0xbcyi {
  width: 4.752px;
  height: 6.252px;
  x: 28.654px;
  y: 18.626px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

.pkpaaxb-j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.56 29.108a2 2 0 0 0-2 2V42.5H38.5a4 4 0 0 0 4-4v-9.392z");
}

.r4qmnofrs {
  width: 4.752px;
  height: 6.252px;
  x: 19.561px;
  y: 18.626px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

</style>
