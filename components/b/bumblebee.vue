<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fm_4658_x"/><path class="d1agkjv9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bumblebee" /></template>
<style>
.d1agkjv9j {
  d: path("M11 8.5c-2-3-.5-6 2-5c2 .75 1.5 3.5-.5 5.25M11 9v10m4.5-10.25v10.5m5-5.25h1.25");
}

.fm_4658_x {
  d: path("M6.5 14a7 5.5 0 1 0 14 0a7 5.5 0 1 0-14 0Zm-4 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
