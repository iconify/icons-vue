<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wd9z8wb-e"/><path class="vr-x6ab1i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fatigue" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vr-x6ab1i {
  fill: currentColor;
  d: path("M15.75 17h1.5v1.5h-1.5Z");
}

.wd9z8wb-e {
  d: path("M11.472 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5q.49 0 .963.039M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm7.75 8.5H21V20h-6.75Zm7.5 1.5v1.5");
}

</style>
