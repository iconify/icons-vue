<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mzrntjbkl"/><path class="k4imskycm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:basketball-rebound" /></template>
<style>
.k4imskycm {
  d: path("M4.75 13.25q3.25 3.25 0 6.5m6.5-6.5q-3.25 3.25 0 6.5");
}

.mzrntjbkl {
  d: path("M20.5 3v11M3 3.5l15 4l-5 2.5m-9.5 6.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm0 0h9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
