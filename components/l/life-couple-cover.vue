<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m9w4wmbio"/><path class="x2muq7zse"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:life-couple-cover" /></template>
<style>
.m9w4wmbio {
  d: path("M3.5 7a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm11 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-12 13c0-3.75 1.75-6 4-6c.6 0 1.1.1 1.5.25M21.5 20c0-3.75-1.75-6-4-6c-.6 0-1.1.1-1.5.25M8.75 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x2muq7zse {
  d: path("M11.25 16.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
