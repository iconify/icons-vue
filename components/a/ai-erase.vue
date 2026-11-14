<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kz80cibvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ai-erase" /></template>
<style>
.kz80cibvq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14.5v-3h3m-3 7v3h3m3.5 0h3M10.404 9.707l5.303-5.303a1.75 1.75 0 0 1 2.475 0l1.414 1.414a1.75 1.75 0 0 1 0 2.475l-5.303 5.303a1.75 1.75 0 0 1-2.475 0l-1.414-1.414a1.75 1.75 0 0 1 0-2.475m1.237-1.237l3.889 3.889M18 14.5q.5 3 3.5 3.5q-3 .5-3.5 3.5q-.5-3-3.5-3.5q3-.5 3.5-3.5");
}

</style>
