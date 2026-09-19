<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y4gfr-1of"/><circle class="c19f-i_mj"/><circle class="frxoacz5k"/><circle class="xziwbzbyz"/><circle class="pm6i8ccee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cuto" /></template>
<style>
.c19f-i_mj {
  cx: 9.309px;
  cy: 9.5px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.frxoacz5k {
  cx: 9.309px;
  cy: 38.5px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pm6i8ccee {
  cx: 38.691px;
  cy: 9.5px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xziwbzbyz {
  cx: 38.309px;
  cy: 38.5px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y4gfr-1of {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.589 5.602L34.8 10.389m6.719-3.717l-5.65 5.65m6.72-3.72L37.8 13.389M9.31 34.5v-21m25 25h-21m25-25v21m-25-25h21");
}

</style>
