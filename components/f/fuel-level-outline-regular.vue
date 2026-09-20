<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l2nbo7bgf"/><path class="m-p3hbclp"/><path class="exre5jj_d"/><path class="jwnes9bsk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fuel-level-outline-regular" /></template>
<style>
.exre5jj_d {
  d: path("m12 15 -4.5 -4.5");
}

.jwnes9bsk {
  d: path("M8 19h8");
}

.l2nbo7bgf {
  d: path("M4 15a8 8 0 0 1 16 0");
}

.m-p3hbclp {
  d: path("M4 15h16");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
