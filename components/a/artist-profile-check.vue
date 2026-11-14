<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jl7amebrr"/><path class="jhegndbuk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:artist-profile-check" /></template>
<style>
.jhegndbuk {
  d: path("M9 9.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM6.5 21c0-3.5 2.5-5.5 5.5-5.5q.597 0 1.161.104M14.75 18l2 2L21 15.75");
}

.jl7amebrr {
  d: path("M13.8 21H3V3h18v8.8m0 7.9V21h-1.3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
