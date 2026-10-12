<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="zt0uddb5s"/><path class="erg1mi22d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crossword-sharp" /></template>
<style>
.erg1mi22d {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 4h4v4h-4Zm1 2h2M4 16h4v4H4Zm1 2h2");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zt0uddb5s {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3h18v18H3zm6 0v18m6-18v18M3 9h18M3 15h18");
}

</style>
