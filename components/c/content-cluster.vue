<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="audwk_b3u"/><path class="lni3wcb-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:content-cluster" /></template>
<style>
.audwk_b3u {
  fill: currentColor;
  d: path("M9 12.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.lni3wcb-p {
  d: path("M10 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-6.5 14a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm13 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM12 6.5v3m-2.25 5L7 17.25m7.25-2.75L17 17.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
