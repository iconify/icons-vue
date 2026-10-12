<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ya68oebpk"/><path class="trb-fmbec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gauze-pad-sharp" /></template>
<style>
.trb-fmbec {
  d: path("M2.75 10.75h5v2.5h-5zm13.5 0h5v2.5h-5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ya68oebpk {
  d: path("M5.25 5.25h13.5v13.5H5.25zm0 5l5-5m-5 10l10-10m-6.5 13.5l10-10m-5 10l5-5");
}

</style>
