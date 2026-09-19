<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t3v8c8b1i"/><circle class="x18rz_cgq"/><path class="v7wkco87k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dmss" /></template>
<style>
.t3v8c8b1i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.474 26.318l17.112 17.196a3.346 3.346 0 0 0 4.732.012l17.196-17.112a3.346 3.346 0 0 0 .012-4.732L26.414 4.486a3.346 3.346 0 0 0-4.732-.012L4.486 21.586a3.346 3.346 0 0 0-.012 4.732");
}

.v7wkco87k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.935 23.13a3.065 3.065 0 0 1-3.066-3.065c0-1.128.617-2.104 1.525-2.636A7 7 0 0 0 24 17a7 7 0 1 0 7 7a7 7 0 0 0-.43-2.394a3.05 3.05 0 0 1-2.635 1.525");
}

.x18rz_cgq {
  cx: 24px;
  cy: 24px;
  r: 11.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
