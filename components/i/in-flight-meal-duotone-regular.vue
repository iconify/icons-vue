<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="akhe8vn1q"/><path class="g1rk1vbex"/><path class="yqpe6ac0e"/><path class="dk2_9r6pl"/><path class="l8dn9jbyp"/><path class="sg1q03b0n"/><path class="zgowxqjxj"/><path class="o8od38cnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:in-flight-meal-duotone-regular" /></template>
<style>
.akhe8vn1q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 15h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.dk2_9r6pl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 18h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g1rk1vbex {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2.5 15a6.5 6.5 0 0 1 13 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l8dn9jbyp {
  d: path("M2 15h20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o8od38cnm {
  d: path("M4 18h16");
}

.sg1q03b0n {
  d: path("M2.5 15a6.5 6.5 0 0 1 13 0");
}

.yqpe6ac0e {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15.5 15V8H21v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zgowxqjxj {
  d: path("M15.5 15V8H21v7");
}

</style>
