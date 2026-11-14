<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nngizebsx"/><path class="dwk2gcb3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cover-note" /></template>
<style>
.dwk2gcb3m {
  d: path("M19.5 15h-4a1.5 1.5 0 0 0-1.5 1.5v4M8 9h8m-8 4h5");
}

.nngizebsx {
  d: path("M4.5 4.5h15V15L14 20.5H4.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
