<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o4e904b0z"/><path class="nl-i_fbec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:digital-microscope" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nl-i_fbec {
  d: path("M4.25 3.036za1.75 1.75 0 0 1 2.391.64l2.25 3.898a1.75 1.75 0 0 1-.641 2.39a1.75 1.75 0 0 1-2.391-.64l-2.25-3.898a1.75 1.75 0 0 1 .641-2.39M4 14h6.5m6.125-7.5h2.25A2.625 2.625 0 0 1 21.5 9.125v1.75a2.625 2.625 0 0 1-2.625 2.625h-2.25A2.625 2.625 0 0 1 14 10.875v-1.75A2.625 2.625 0 0 1 16.625 6.5M17.75 10h.01m-.01 3.5v7m-2.25 0H20");
}

.o4e904b0z {
  d: path("M3 20.5h9.5m-2 0V12c0-2.5-1-4-2.75-4.5");
}

</style>
