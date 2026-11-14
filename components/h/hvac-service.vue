<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pm3avnbeg"/><path class="xb8-ucc0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hvac-service" /></template>
<style>
.pm3avnbeg {
  d: path("M10 10c-1.5 1-4.75.5-5.5-1.75C4 6.5 5.75 4.5 7.5 5.5C9 6.5 9.25 8 10 10Zm2 0c-.25-2 2-4.5 4.25-4c1.75.5 2.5 3 .75 4c-1.5.75-3 .25-5 0Zm-1 1.75c1.75.75 2.75 3.75 1.25 5.5C11 18.5 8.5 18 8.5 16c0-1.75 1.25-2.75 2.5-4.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xb8-ucc0r {
  d: path("M9.5 10.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm11.72 5.903a2 2 0 1 1-1.623-1.623M15 21l2.75-2.75");
}

</style>
