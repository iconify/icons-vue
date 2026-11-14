<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="umrs8bc4q"/><path class="cpwizubfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fossil-in-rock" /></template>
<style>
.cpwizubfo {
  d: path("M8.25 10C6.5 10 5.5 11 5.5 12.25s1 2.25 2.75 2.25Zm0 2.25h8.25M11 10v4.5m2.75-4.5v4.5m4.75-4.25l-2 2l2 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.umrs8bc4q {
  d: path("m2.829 10.578l1.679-4.701A2.63 2.63 0 0 1 6.43 4.194l5.038-1.08a2.6 2.6 0 0 1 1.065-.007l5.27 1.054a2.63 2.63 0 0 1 2.054 2.033l1.464 6.955a2.63 2.63 0 0 1-.185 1.641l-1.932 4.185A2.63 2.63 0 0 1 16.82 20.5H7.796a2.625 2.625 0 0 1-2.447-1.674l-2.494-6.414a2.63 2.63 0 0 1-.026-1.834");
}

</style>
