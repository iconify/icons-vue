<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="nx0kqvb4y"/><circle class="tomf5p4vf"/><circle class="gnu6s1ksn"/><circle class="dtqe5xsvr"/><path class="khd4kgbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:leto-s-deckem" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dtqe5xsvr {
  cx: 17px;
  cy: 9px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gnu6s1ksn {
  cx: 31px;
  cy: 9px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.khd4kgbov {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17 10.75V14m7-3.25V14m7-3.25V14m3 11.5c.816 8-1.76 17.001-10 20c-.255-5.74.006-17.999 10-20");
}

.nx0kqvb4y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14 25.5c-.816 8 1.76 17.001 10 20c.255-5.74-.006-17.999-10-20m10 20V24M14 14c0 5.523 4.477 10 10 10s10-4.477 10-10z");
}

.tomf5p4vf {
  cx: 24px;
  cy: 9px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
