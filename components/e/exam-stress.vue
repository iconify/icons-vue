<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rg8vv8bhj"/><path class="mm8t81b0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:exam-stress" /></template>
<style>
.mm8t81b0c {
  d: path("M8.5 16.5c1.5-2 2.5.5 3.5-1.25c1 1.75 2-.75 3.5 1.25M7 6.5l3.5 1.25M17 6.5l-3.5 1.25");
}

.rg8vv8bhj {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0ZM9 10h.01M15 10h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
