<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esa0accle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ear-plugs" /></template>
<style>
.esa0accle {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 16V7a3 3 0 0 1 6 0v9Zm11 0V7a3 3 0 0 1 6 0v9Zm-8 0q0 4.5 5.5 4.5t5.5-4.5");
}

</style>
