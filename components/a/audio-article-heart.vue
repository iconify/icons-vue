<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bz8gglbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:audio-article-heart" /></template>
<style>
.bz8gglbdv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9.5v5M7.5 5v14M12 2.5v19M16.5 5v7M21 8v3.5M18 21l-2.5-2.5A1.75 1.75 0 0 1 18 16a1.75 1.75 0 0 1 2.5 2.5Z");
}

</style>
