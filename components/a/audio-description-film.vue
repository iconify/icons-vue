<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="red50_bch"/><path class="fx0lhxetn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:audio-description-film" /></template>
<style>
.fx0lhxetn {
  d: path("M8.5 6.5L13 9l-4.5 2.5Zm4.5 8a1.5 1.5 0 0 1 1.5-1.5H20a1.5 1.5 0 0 1 1.5 1.5V18a1.5 1.5 0 0 1-1.5 1.5h-3l-2.5 2v-2A1.5 1.5 0 0 1 13 18Z");
}

.red50_bch {
  d: path("M10.2 15H2.5V3h16v7.2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
