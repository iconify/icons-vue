<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ped5oacqv"/><path class="ywe9fjbpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:magnifier-glass" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ped5oacqv {
  d: path("M9.75 2.75a7 7 0 1 1 0 14a7 7 0 1 1 0-14m7.69 12.04l2.47 2.47q1.24 1.24 0 2.48l-.17.17q-1.24 1.24-2.48 0l-2.47-2.47q-1.24-1.24 0-2.48l.17-.17q1.24-1.24 2.48 0");
}

.ywe9fjbpp {
  d: path("M6.25 9.75a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
