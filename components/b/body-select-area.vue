<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlyucac0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:body-select-area" /></template>
<style>
.vlyucac0x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.736 19.5h-.486c-.5 0-1-.5-1-1L10 15a.781.781 0 0 0-1.5 0l-.25 3.5c0 .5-.5 1-1 1h-1c-.75 0-1.25-.5-1-1.25L6 14l.5-2l-1.25 1.5c-.25.5-.5.75-1.25.75c-1 0-1.5-.5-1.25-1.5l2-2.5C5 9 6 8.75 7.25 8.75h4c1.25 0 2.25.25 2.5 1.5l1.156 1.445M7.25 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM14.5 16v-1.5H16m4 0h1.5V16m0 4v1.5H20m-4 0h-1.5V20m2.75-5.5h1.5m-1.5 7h1.5m-4.25-4.25v1.5m7-1.5v1.5");
}

</style>
