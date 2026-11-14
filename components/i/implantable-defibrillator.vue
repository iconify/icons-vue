<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i7x1owbls"/><path class="f154f315p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:implantable-defibrillator" /></template>
<style>
.f154f315p {
  d: path("M10.25 8.75L7.75 13h3l-2.5 4.25m6.5-8.75c3.25-3 6.75-1 6.25 2.75c-.5 3.25-.75 6.25.5 10.25");
}

.i7x1owbls {
  d: path("M5.5 6H13a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5.5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
