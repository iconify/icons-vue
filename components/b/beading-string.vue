<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nom2y0b4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beading-string" /></template>
<style>
.nom2y0b4w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 17.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM9.5 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM15 6.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-6.75 9.25l2-2m3.5-3.5l2-2");
}

</style>
