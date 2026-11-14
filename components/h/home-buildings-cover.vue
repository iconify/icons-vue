<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mjnf_wb3z"/><path class="yuf_v5apr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:home-buildings-cover" /></template>
<style>
.mjnf_wb3z {
  d: path("M3.5 9L12 2.5L20.5 9v12.5h-17Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yuf_v5apr {
  d: path("M10 10h4v3.5h-4Zm.25 11.5v-3.25a1.75 1.75 0 0 1 3.5 0v3.25");
}

</style>
