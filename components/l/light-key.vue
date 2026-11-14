<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o931eccnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:light-key" /></template>
<style>
.o931eccnz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.559 5.273l.881-1.542a1.5 1.5 0 0 1 1.657-.713l7.192 1.754a1.5 1.5 0 0 1 .938 2.218l-2.977 5.06a1.5 1.5 0 0 1-2.371.282L6.782 7.059a1.5 1.5 0 0 1-.223-1.786M10 10.25V18m-4 3.5l4-3.5l4 3.5");
}

</style>
