<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eyyjdibvl"/><path class="y7h7c3bji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blog-post-edit" /></template>
<style>
.eyyjdibvl {
  d: path("M11.9 21.5H3.5v-19h16v8.1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y7h7c3bji {
  d: path("M6.5 5.5h10V11h-10Zm0 9h5m-5 3.5H10m4.75 3.5l.5-2.75l4.5-4.5L22 16.5L17.5 21Z");
}

</style>
