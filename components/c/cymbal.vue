<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ra0qjkbfr"/><path class="jbnubzvsj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cymbal" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jbnubzvsj {
  d: path("M9.75 8.5c0-1.8 1-3.25 2.25-3.25s2.25 1.45 2.25 3.25ZM12 5.25v-2.5m0 9.5v7.5m0 0l-4 1.5m4-1.5l4 1.5");
}

.ra0qjkbfr {
  d: path("M2.75 10.75c0-1.5 4.1-2.5 9.25-2.5s9.25 1 9.25 2.5c0 .8-4.1 1.5-9.25 1.5s-9.25-.7-9.25-1.5");
}

</style>
