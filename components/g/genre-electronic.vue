<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyho4dx8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:genre-electronic" /></template>
<style>
.uyho4dx8z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.627 5.441l-5.356 5.484a1.369 1.369 0 0 0 .979 2.325h1.108a1.5 1.5 0 0 1 1.41 2.013L10 17.375a.895.895 0 0 0 1.495.916l5.373-5.756a1.358 1.358 0 0 0-.993-2.285h-1.001a1.5 1.5 0 0 1-1.414-2.002l.665-1.873a.904.904 0 0 0-1.498-.934");
}

</style>
