<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dw3mdsbcd"/><path class="l47pq7b7k"/><circle class="szj4eqblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lesspass" /></template>
<style>
.dw3mdsbcd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 3.5L44.5 24L24 44.5L3.5 24Z");
}

.l47pq7b7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.998 11.753a5.28 5.28 0 0 0-1.541 10.33v13.67h5.828v-2.742h-2.742v-1.913h2.742v-2.74h-2.742v-6.275a5.281 5.281 0 0 0-1.545-10.33");
}

.szj4eqblm {
  cx: 24px;
  cy: 16.998px;
  r: 2.42px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
