<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ac8v_-t5w"/><path class="hhzugwbsl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bandaged-casualty" /></template>
<style>
.ac8v_-t5w {
  d: path("M4.5 19.75c0-3.25 3.25-5.5 7.5-5.5s7.5 2.25 7.5 5.5c0 .6-.4 1-1 1h-13c-.6 0-1-.4-1-1ZM7.5 7a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Z");
}

.hhzugwbsl {
  d: path("M8.25 4.5q3.75 1.5 7.5 0M7.5 7.25q4.5 1.5 9 0l3-2.25m-3 2.25l3 2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
