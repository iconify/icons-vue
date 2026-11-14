<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wb2xo4-5f"/><path class="m6h02bxbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dog-breed-bulldog" /></template>
<style>
.m6h02bxbp {
  d: path("M8 17c.75-1.75 2.5-2 4-1.25c1.5-.75 3.25-.5 4 1.25m-4-4h.01M9 9.75h.01m5.99 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wb2xo4-5f {
  d: path("m4.5 10l-1 .5l-1-3.75L6.25 5.5C8 4.75 10 4.5 12 4.5s4 .25 5.75 1l3.75 1.25l-1 3.75l-1-.5v4c0 4.5-3 6.5-7.5 6.5s-7.5-2-7.5-6.5Z");
}

</style>
