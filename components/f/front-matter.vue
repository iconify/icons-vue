<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d_-ir7pzy"/><path class="i1yj1kvwv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:front-matter" /></template>
<style>
.d_-ir7pzy {
  d: path("M4.5 2.5h15v19h-15Zm3 4.5h9m-7 3.5h5M9.25 15v3.5");
}

.i1yj1kvwv {
  d: path("m12.25 15l1.5 3.5l1.5-3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
