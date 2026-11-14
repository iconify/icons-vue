<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6gjitoca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:allergen-label" /></template>
<style>
.c6gjitoca {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.464 14.061a2 2 0 0 0-.214.189c-1 1-1 3-2.5 4.5c-1.75 1.75-4.5 2-6.5 0s-1.75-4.75 0-6.5c1.5-1.5 3.5-1.5 4.5-2.5s1-3 2.5-4.5c1.75-1.75 4.5-2 6.5 0c1.49 1.49 1.731 3.397 1.033 4.996M14 7h.01M7 14h.01M10 17h.01M18 13l4 8.75h-8Zm0 3.25v1.5m0 2h.01");
}

</style>
