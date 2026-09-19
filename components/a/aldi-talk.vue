<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dt0_d4ygj"/><rect class="j3s9ivbxi"/><path class="xv5tr4bos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aldi-talk" /></template>
<style>
.dt0_d4ygj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.875 10.499L14.5 27.501m10.297-17.002l-6.375 17.002m10.297-17.002l-6.375 17.002m7.117-12.752h.871M27.867 19h4.039m-5.632 4.251H33.5");
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

.xv5tr4bos {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.065 33.04v5.373h2.687M15.791 33.04h3.56m-1.78 5.373V33.04m11.75 0v5.373m2.888 0l-2.212-2.686l2.212-2.669m-2.212 2.669h-.676m-9.563 2.67l1.745-5.357m1.748 5.373l-1.748-5.373m1.163 3.576h-2.327");
}

</style>
