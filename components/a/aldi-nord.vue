<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dt0_d4ygj"/><rect class="j3s9ivbxi"/><path class="u4mnlccba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aldi-nord" /></template>
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

.u4mnlccba {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.298 38.413V33.04h1.209a2.35 2.35 0 0 1 2.35 2.35v.673a2.35 2.35 0 0 1-2.35 2.35zm-5.305 0V33.04h1.759c.995 0 1.8.808 1.8 1.805s-.806 1.804-1.8 1.804h-1.76m1.76 0l1.759 1.763m-14.369.001V33.04l3.56 5.373V33.04m1.895 3.594a1.78 1.78 0 0 0 3.56 0V34.82a1.78 1.78 0 0 0-3.56 0z");
}

</style>
