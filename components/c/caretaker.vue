<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnciu1lky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:caretaker" /></template>
<style>
.dnciu1lky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM3 20.5c0-3.75 2.75-6 6.5-6c.893 0 1.73.128 2.486.373M18 21l-2.75-2.75c-1-1-1-2.75.25-3.5c1-.6 2-.15 2.5.75c.5-.9 1.5-1.35 2.5-.75c1.25.75 1.25 2.5.25 3.5Z");
}

</style>
