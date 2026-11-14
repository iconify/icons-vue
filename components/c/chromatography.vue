<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="trh2ghbkw"/><path class="is-2d1bzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chromatography" /></template>
<style>
.is-2d1bzl {
  fill: currentColor;
  d: path("M9.5 6.25a1 1 0 1 0 2 0a1 1 0 1 0-2 0ZM11.75 11a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-2.5 5.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.trh2ghbkw {
  d: path("M6.5 2.5h11v19h-11Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
