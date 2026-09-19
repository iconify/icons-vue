<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="diw9qinlp"/><circle class="izagttbos"/><circle class="qkmaf62fy"/><path class="sw0z-tb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kaspersky-password-manager" /></template>
<style>
.diw9qinlp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.5 2.902l-16.021 9.25a3 3 0 0 0-1.5 2.598v18.5a3 3 0 0 0 1.5 2.598l16.021 9.25a3 3 0 0 0 3 0l16.021-9.25a3 3 0 0 0 1.5-2.598v-18.5a3 3 0 0 0-1.5-2.598L25.5 2.902a3 3 0 0 0-3 0");
}

.izagttbos {
  cx: 24px;
  cy: 18px;
  r: 6px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qkmaf62fy {
  cx: 24px;
  cy: 15.696px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sw0z-tb6y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.034 23.669v3.427l1.26 1.173l-1.26 1.173l1.26 1.173l-1.26 1.173v2.745L24 35.79l1.965-1.257V23.67");
}

</style>
