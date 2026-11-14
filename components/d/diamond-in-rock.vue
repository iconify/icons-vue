<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pkq_f9e4o"/><path class="x7sizlb8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:diamond-in-rock" /></template>
<style>
.pkq_f9e4o {
  d: path("M2.5 12L5 5l6-2.5l7 2l3.5 6.5l-2.5 8.5l-7 2L5 19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x7sizlb8l {
  d: path("m7.5 10l2-2.5h5l2 2.5l-4.5 6Zm0 0h9");
}

</style>
