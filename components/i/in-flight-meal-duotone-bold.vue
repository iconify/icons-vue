<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ycftzzhuq"/><path class="hnba5kd6n"/><path class="z_cql0b5h"/><path class="km2_vvbqp"/><path class="l8dn9jbyp"/><path class="sg1q03b0n"/><path class="zgowxqjxj"/><path class="o8od38cnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:in-flight-meal-duotone-bold" /></template>
<style>
.hnba5kd6n {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2.5 15a6.5 6.5 0 0 1 13 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.km2_vvbqp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 18h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l8dn9jbyp {
  d: path("M2 15h20");
}

.o8od38cnm {
  d: path("M4 18h16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sg1q03b0n {
  d: path("M2.5 15a6.5 6.5 0 0 1 13 0");
}

.ycftzzhuq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 15h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z_cql0b5h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M15.5 15V8H21v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zgowxqjxj {
  d: path("M15.5 15V8H21v7");
}

</style>
