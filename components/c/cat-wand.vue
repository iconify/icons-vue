<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="n941uqb4u"/><path class="oupbif3sg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cat-wand" /></template>
<style>
.n941uqb4u {
  d: path("m3 21l11-11m0 0c-1.5-3.5 0-6.5 3.25-7.5C18 6 17 8.5 14 10Z");
}

.oupbif3sg {
  d: path("M14 10c2-3 5-3.75 7.5-3c-1.25 3.25-4 4.5-7.5 3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
