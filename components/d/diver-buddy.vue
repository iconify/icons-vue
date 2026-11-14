<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_ru-l1ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:diver-buddy" /></template>
<style>
.o_ru-l1ki {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6.5a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-.75L6.5 9l-1.25 1.5H4.5a2 2 0 0 1-2-2Zm11 9a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2h-.75L17.5 18l-1.25 1.5h-.75a2 2 0 0 1-2-2Zm-3-8c3.5.5 7 2.5 7 6");
}

</style>
