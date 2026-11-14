<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c1wtwhxjt"/><path class="h_l-qwbpg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:encryption" /></template>
<style>
.c1wtwhxjt {
  d: path("m12 2.5l8 3v6c0 5-3.5 8.25-8 10c-4.5-1.75-8-5-8-10v-6Z");
}

.h_l-qwbpg {
  d: path("M9 11h6v5H9Zm1 0V9.5a2 2 0 0 1 4 0V11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
