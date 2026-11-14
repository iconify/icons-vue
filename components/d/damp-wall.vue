<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bmxpiz1hx"/><path class="dp92yebxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:damp-wall" /></template>
<style>
.bmxpiz1hx {
  d: path("M2.5 2.5h19v19h-19Zm0 4.5h19m-19 4.5h19M9 2.5V7m6.5-4.5V7m-10 0v4.5M12 7v4.5M18.5 7v4.5");
}

.dp92yebxz {
  d: path("M8 14s-1.75 2.25-1.75 3.5a1.75 1.75 0 0 0 3.5 0C9.75 16.25 8 14 8 14Zm7.5 0s-1.75 2.25-1.75 3.5a1.75 1.75 0 0 0 3.5 0c0-1.25-1.75-3.5-1.75-3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
