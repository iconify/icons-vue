<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y0bxu8b9k"/><path class="k6xh-ab3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:football-jersey" /></template>
<style>
.k6xh-ab3y {
  d: path("M8.5 3L12 7l3.5-4m-9 11.5h11");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y0bxu8b9k {
  d: path("M8.5 3L3 5.5V11h3.5v10h11V11H21V5.5L15.5 3Z");
}

</style>
