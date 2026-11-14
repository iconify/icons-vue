<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uv8-9cc6n"/><path class="afrk1w6mu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bride-groom-pictogram" /></template>
<style>
.afrk1w6mu {
  d: path("m16 13.5l1.5 2.25L19 13.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uv8-9cc6n {
  d: path("M2.5 7.5q4-5.5 8 0Zm1.5 0a2.5 2.5 0 0 0 5 0m-6.5 13c0-4.5 1.5-7.25 4-7.25s4 2.75 4 7.25m4.5-13a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-1.5 13c0-4.5 1.5-7.25 4-7.25s4 2.75 4 7.25");
}

</style>
