<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x69qejfap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lead-hot" /></template>
<style>
.x69qejfap {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.672 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.115 0 2.16.155 3.097.442M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm12 6c2 2 3.25 3.75 3.25 5.75a3.25 3.25 0 0 1-6.5 0q0-2.25 1.5-3.75c.25 1 .75 1.5 1.25 1.75c0-1.25 0-2.5.5-3.75Z");
}

</style>
