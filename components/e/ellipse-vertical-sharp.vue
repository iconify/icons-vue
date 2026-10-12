<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="q8yntsl5z"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ellipse-vertical-sharp" /></template>
<style>
.q8yntsl5z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12a9.25 6.5 0 1 0 18.5 0a9.25 6.5 0 1 0-18.5 0Z");
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
