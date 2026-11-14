<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m39fh0bnx"/><path class="ky1_6hkmb"/><path class="o7f9npbyw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:diarrhoea" /></template>
<style>
.ky1_6hkmb {
  fill: currentColor;
  d: path("M13 3c1 1.25 1.5 2 1.5 2.75s-.65 1.5-1.5 1.5s-1.5-.75-1.5-1.5S12 4.25 13 3Zm5-.5c1 1.25 1.5 2 1.5 2.75s-.65 1.5-1.5 1.5s-1.5-.75-1.5-1.5s.5-1.5 1.5-2.75Z");
}

.m39fh0bnx {
  d: path("M3 2.5h5v8H3ZM3 11h13.5c0 3.75-2.25 6.25-5.5 6.25H9.25L10 21.5H4.75L5 16.75C3.75 15.5 3 13.5 3 11Z");
}

.o7f9npbyw {
  d: path("M19 9.5L20.5 8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
