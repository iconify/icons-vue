<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h725mi3uh"/><path class="s9z-8ngvj"/><path class="w5607a_pe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab-results-file" /></template>
<style>
.h725mi3uh {
  d: path("M2.5 18.5v-13c0-1.1.9-2 2-2H9l2 2h8.5c1.1 0 2 .9 2 2v11c0 1.1-.9 2-2 2h-15c-1.1 0-2-.9-2-2Zm0-9.75h19");
}

.s9z-8ngvj {
  d: path("M10.5 11v4.75c0 .85.65 1.5 1.5 1.5s1.5-.65 1.5-1.5V11m-4 0h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w5607a_pe {
  fill: currentColor;
  d: path("M10.5 14h3v1.75c0 .85-.65 1.5-1.5 1.5s-1.5-.65-1.5-1.5Z");
}

</style>
