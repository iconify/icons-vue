<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8jl8rbrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cursor-not-allowed" /></template>
<style>
.y8jl8rbrz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 3.5l11 4.5l-5 1.5l-2 5Zm10.25 14a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0ZM15 15l5 5");
}

</style>
