<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xvo3w7boi"/><path class="awxfzrb9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:doctor-female" /></template>
<style>
.awxfzrb9z {
  d: path("M10.75 6.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm1.25 0h.01M7.5 9.5c-.75 1.5-.75 3-.25 4.5m9.25-4.5c.75 1.5.75 3 .25 4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xvo3w7boi {
  d: path("M4 20c0-3.25 3.5-5.5 8-5.5s8 2.25 8 5.5c0 .6-.4 1-1 1H5c-.6 0-1-.4-1-1ZM7.5 8a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm.25-1.25h2.75m3 0h2.75");
}

</style>
