<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yugtg-26e"/><path class="xglcvc7pz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:brain-neurons" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xglcvc7pz {
  d: path("M5.5 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5-4.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5 4.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-7.25-1l2.5-2.5m2.5 0l2.5 2.5");
}

.yugtg-26e {
  d: path("M6 16.5c-3-.5-4-4-2.5-6.5c-.75-3.25 2-6 5-5.5c2-2 6-2 8 0c3 0 5.25 3 4.5 6c1 2.5-.5 5.5-3.5 5.5v3.5c0 1-1 1.5-2 1l-2-3.5c-2 1-5.5 1-7.5-.5Z");
}

</style>
