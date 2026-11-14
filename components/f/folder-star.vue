<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q3wixnhae"/><path class="x4npsgbrr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:folder-star" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q3wixnhae {
  d: path("M3 7a2 2 0 0 1 2-2h4.5l2 2H19a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

.x4npsgbrr {
  d: path("m12.47 10.853l.118.277a1.5 1.5 0 0 0 1.247.905l.3.027a.511.511 0 0 1 .29.894l-.227.198a1.5 1.5 0 0 0-.476 1.466l.067.293a.511.511 0 0 1-.76.553l-.259-.155a1.5 1.5 0 0 0-1.54 0l-.259.155a.511.511 0 0 1-.76-.553l.067-.293a1.5 1.5 0 0 0-.476-1.466l-.227-.198a.511.511 0 0 1 .29-.894l.3-.027a1.5 1.5 0 0 0 1.247-.905l.118-.277a.511.511 0 0 1 .94 0");
}

</style>
