<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uq71rmbyn"/><path class="ueqen8csy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drone" /></template>
<style>
.ueqen8csy {
  d: path("M9.75 9.75L7.5 7.5m6.75 2.25L16.5 7.5m-2.25 6.75l2.25 2.25m-6.75-2.25L7.5 16.5M2 6a3.5 2 0 1 0 7 0a3.5 2 0 1 0-7 0Zm13 0a3.5 2 0 1 0 7 0a3.5 2 0 1 0-7 0ZM2 18a3.5 2 0 1 0 7 0a3.5 2 0 1 0-7 0Zm13 0a3.5 2 0 1 0 7 0a3.5 2 0 1 0-7 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uq71rmbyn {
  fill: currentColor;
  d: path("M9.75 9.75h4.5v4.5h-4.5Z");
}

</style>
