<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oftlruavh"/><path class="epqfxn5zz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eye-tear" /></template>
<style>
.epqfxn5zz {
  d: path("M9 9a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm7 7.75L17.5 19a1.75 1.75 0 1 1-3 0Z");
}

.oftlruavh {
  d: path("M2.5 9C5 4.75 8.25 3 12 3s7 1.75 9.5 6c-2.5 4.25-5.75 6-9.5 6s-7-1.75-9.5-6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
