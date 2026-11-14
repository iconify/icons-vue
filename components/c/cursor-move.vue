<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0bpp__2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cursor-move" /></template>
<style>
.m0bpp__2i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 12h12m-6-6v12m-8.171-7.139l.421-.361a1.06 1.06 0 0 1 1.75.805v1.39a1.06 1.06 0 0 1-1.75.805l-.421-.361a1.5 1.5 0 0 1 0-2.278m16.342 0l-.421-.361a1.06 1.06 0 0 0-1.75.805v1.39a1.06 1.06 0 0 0 1.75.805l.421-.361a1.5 1.5 0 0 0 0-2.278m-9.31-7.032l-.361.421A1.06 1.06 0 0 0 11.305 6h1.39a1.06 1.06 0 0 0 .805-1.75l-.361-.421a1.5 1.5 0 0 0-2.278 0m0 16.342l-.361-.421a1.06 1.06 0 0 1 .805-1.75h1.39a1.06 1.06 0 0 1 .805 1.75l-.361.421a1.5 1.5 0 0 1-2.278 0");
}

</style>
