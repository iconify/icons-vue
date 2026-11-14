<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oze5yib3i"/><path class="yekc8woru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ar-placement" /></template>
<style>
.oze5yib3i {
  d: path("m12 4l4 2v6l-4 2l-4-2V6ZM8 6l4 2l4-2m-4 2v6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yekc8woru {
  d: path("M6 13.75L3.5 15l8.5 4.25L20.5 15L18 13.75");
}

</style>
