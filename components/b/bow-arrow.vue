<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eh3gfms5p"/><path class="e5ragzjjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bow-arrow" /></template>
<style>
.e5ragzjjw {
  d: path("M7 9.25L9.5 12L7 14.75");
}

.eh3gfms5p {
  d: path("M7 2.5c8 3 8 16 0 19m0-19L3 12l4 9.5M3 12h18.5M18 8.5l3.5 3.5l-3.5 3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
