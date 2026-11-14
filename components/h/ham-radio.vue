<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z14rd9zjq"/><path class="m9iyqib1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ham-radio" /></template>
<style>
.m9iyqib1c {
  d: path("M6 15.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM19.031 3.75a3.5 3.5 0 0 1 0 3.5m-6.062 0a3.5 3.5 0 0 1 0-3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z14rd9zjq {
  d: path("M3 10.5h18v10H3Zm13 0v-5");
}

</style>
