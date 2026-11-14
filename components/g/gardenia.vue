<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zy_es_tvb"/><path class="bvbuzgqtp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gardenia" /></template>
<style>
.bvbuzgqtp {
  d: path("M10.75 9a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0ZM12 21.5c-2.5 0-6.5-1-8-4c3.5 0 6.5 1 8 4Zm0 0c2.5 0 6.5-1 8-4c-3.5 0-6.5 1-8 4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zy_es_tvb {
  d: path("M10 6.25a2.5 2.5 0 1 1 4 0A2.5 2.5 0 1 1 15.25 10A2.5 2.5 0 1 1 12 12.5A2.5 2.5 0 1 1 8.75 10A2.5 2.5 0 1 1 10 6.25Z");
}

</style>
