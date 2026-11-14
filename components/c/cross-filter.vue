<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rktheiezo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cross-filter" /></template>
<style>
.rktheiezo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3.5h15L12 11v8.5l-4-2V11Zm13.25 14.25l-.25.25a1.75 1.75 0 0 0 2.5 2.5l.25-.25m-.5-4.5l.25-.25a1.75 1.75 0 0 1 2.5 2.5l-.25.25M17 19l2-2");
}

</style>
