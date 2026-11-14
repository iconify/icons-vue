<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7zmjqb1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coffee-tasting" /></template>
<style>
.g7zmjqb1h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11.75h18q-.5 7.75-9 7.75t-9-7.75ZM2.5 7h11m0 0a3.5 2 0 1 0 7 0a3.5 2 0 1 0-7 0Z");
}

</style>
