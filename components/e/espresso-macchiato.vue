<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x8jtigbxp"/><path class="f-or10kgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:espresso-macchiato" /></template>
<style>
.f-or10kgf {
  d: path("M16.5 11h1a2.5 2.5 0 0 1 0 5h-2m-8-6a3 3 0 0 1 3.25-3.5A2.75 2.75 0 0 1 13.5 10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x8jtigbxp {
  d: path("M5 10h11.5v4a5 5 0 0 1-5 5H10a5 5 0 0 1-5-5Z");
}

</style>
