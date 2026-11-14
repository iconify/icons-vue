<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h-q0e_bdd"/><path class="oav10h6ck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:anaglyph-glasses" /></template>
<style>
.h-q0e_bdd {
  fill: currentColor;
  d: path("M3 13a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.oav10h6ck {
  d: path("M13 13a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM2.5 9h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
