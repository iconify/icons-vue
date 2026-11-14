<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s1czsbckr"/><path class="ezlp2kbjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:avatar-sticker" /></template>
<style>
.ezlp2kbjr {
  d: path("M16.5 3v2.5a2 2 0 0 0 2 2H21M8.5 10a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM6 21c0-3.25 2.5-5 5.5-5s5.5 1.75 5.5 5");
}

.s1czsbckr {
  d: path("M5.5 3h11L21 7.5v11a2.5 2.5 0 0 1-2.5 2.5h-13A2.5 2.5 0 0 1 3 18.5v-13A2.5 2.5 0 0 1 5.5 3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
