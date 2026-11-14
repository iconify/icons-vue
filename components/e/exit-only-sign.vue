<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_3u98bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:exit-only-sign" /></template>
<style>
.m_3u98bug {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14 3.5H6.5a2 2 0 0 0-2 2v13a2 2 0 0 0 2 2H14M9.5 12H21m-3-3l3 3l-3 3");
}

</style>
