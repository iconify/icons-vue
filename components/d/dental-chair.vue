<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y_ia1iuxh"/><path class="tkp0zbbwc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dental-chair" /></template>
<style>
.tkp0zbbwc {
  d: path("M7.75 10.25h6.75v3.25m0 0V21m-4 0h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y_ia1iuxh {
  d: path("M3 2.5h4.5v2.75H3Zm2.75 2.75L9 13.5h8l3.5 4.5");
}

</style>
