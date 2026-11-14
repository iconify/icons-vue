<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s9u-ywozo"/><path class="whbgd8ljj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leaf-cycle" /></template>
<style>
.s9u-ywozo {
  d: path("M18.364 5.636a9 9 0 1 1-12.728 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.whbgd8ljj {
  d: path("M2.75 5.75h3v3M8.5 15.5c0-4.5 2.5-7 7-7c0 4.5-2.5 7-7 7Zm0 0l4-4");
}

</style>
