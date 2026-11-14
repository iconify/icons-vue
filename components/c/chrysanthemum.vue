<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m7emeqbuu"/><path class="xtvc2ts3n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chrysanthemum" /></template>
<style>
.m7emeqbuu {
  d: path("M10.25 6L11 3a1.25 1.25 0 0 1 2 0l.75 3L16 4.25A1.25 1.25 0 0 1 17.75 6L16 8.25L19 9a1.25 1.25 0 0 1 0 2l-3 .75L17.75 14A1.25 1.25 0 0 1 16 15.75L13.75 14L13 17a1.25 1.25 0 0 1-2 0l-.75-3L8 15.75A1.25 1.25 0 0 1 6.25 14L8 11.75L5 11a1.25 1.25 0 0 1 0-2l3-.75L6.25 6A1.25 1.25 0 0 1 8 4.25zM12 18.25v3.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xtvc2ts3n {
  d: path("M10.5 10a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

</style>
