<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y4qb67hob"/><path class="pan3f_chh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bootcamp" /></template>
<style>
.pan3f_chh {
  d: path("M5.5 11.5c-3-5.5-.5-9 4-9S15.5 6 13 10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y4qb67hob {
  d: path("M9 10h11.5v5H14a5 5 0 1 1-5-5Z");
}

</style>
