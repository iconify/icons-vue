<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zox78x7fg"/><path class="ifq_ssbsd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:floating-stairs" /></template>
<style>
.ifq_ssbsd {
  d: path("M3 15.5h5.5v2.75H3ZM9.25 10h5.5v2.75h-5.5Zm6.25-5.5h6v2.75h-6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zox78x7fg {
  d: path("M21.5 2.5v19h-19");
}

</style>
