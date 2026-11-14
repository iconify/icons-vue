<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="njr_habtr"/><path class="l1fvag-td"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:earth-rise" /></template>
<style>
.l1fvag-td {
  d: path("M9.75 9.5a2.25 5 0 1 0 4.5 0a2.25 5 0 1 0-4.5 0Z");
}

.njr_habtr {
  d: path("M2.5 19.5q9.5-4 19 0M7 9.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
