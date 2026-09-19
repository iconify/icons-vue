<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t9_5j_bxu"/><circle class="f2kdhtbpu"/><circle class="kprdmpb1y"/><circle class="sm0zpjp1c"/><circle class="gmwez5buf"/><circle class="ucskfjbnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cheetay" /></template>
<style>
.f2kdhtbpu {
  cx: 27.39px;
  cy: 26.248px;
  r: 9.736px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gmwez5buf {
  cx: 17.529px;
  cy: 11.8px;
  r: 4.101px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kprdmpb1y {
  cx: 26.936px;
  cy: 8.601px;
  r: 4.101px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sm0zpjp1c {
  cx: 36.414px;
  cy: 11.249px;
  r: 4.101px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t9_5j_bxu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.135 38.884a17.252 17.252 0 0 1-28.951-11.372");
}

.ucskfjbnj {
  cx: 11.586px;
  cy: 19.676px;
  r: 4.101px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
