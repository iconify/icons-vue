<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqc71abqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:byline-check" /></template>
<style>
.pqc71abqn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm-2 12c0-3.5 2.5-5.5 5.5-5.5c1.737 0 3.306.67 4.32 1.914M16.5 10h5m-6.75 8l2 2L21 15.75");
}

</style>
