<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="rqgd17bsb"/><path class="v7j7vzb7y"/><path class="fe33edbjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arcade-machine-sharp" /></template>
<style>
.fe33edbjr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 12h.01m4.99.25h.01");
}

.rqgd17bsb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2.75h10.75V15l.39.64l.72 1.22l.39.64v3.75H4.75V17.5l.39-.64l.72-1.22l.39-.64V2.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.v7j7vzb7y {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 5.25h6.5v4h-6.5zM6.25 15h11.5M9.5 12v3");
}

</style>
