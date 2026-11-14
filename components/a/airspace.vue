<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="slj0yrbpw"/><path class="v4-aq7bin"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:airspace" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.slj0yrbpw {
  d: path("m8 4l2.5-1.5L13 4m2 1l2.5 1.5v3m-14 2v3L6 16m2 1l2.5 1.5l1.463-.836M3.5 9.5v-3L6 5");
}

.v4-aq7bin {
  d: path("m3.5 6.5l7 4l7-4m-7 4v8m4.25-.5h6.75M19 18l-2.25-3.5M19 18l-2.25 3.5m-2-5v3");
}

</style>
