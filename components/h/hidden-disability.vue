<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y4rq56bwb"/><path class="p_gvapbwd"/><path class="lyykrhemu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hidden-disability" /></template>
<style>
.lyykrhemu {
  d: path("M10.5 16a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.p_gvapbwd {
  d: path("M16 16a2 2 0 0 1-2 3.5a2 2 0 0 1-4 0A2 2 0 0 1 8 16a2 2 0 0 1 2-3.5a2 2 0 0 1 4 0a2 2 0 0 1 2 3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y4rq56bwb {
  d: path("m6.5 2.5l5.5 8l5.5-8");
}

</style>
