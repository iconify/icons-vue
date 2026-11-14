<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dptozmb-f"/><path class="vhqmbibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crosswinds-sign" /></template>
<style>
.dptozmb-f {
  d: path("M3 2.5h18v15H3Zm9 15v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vhqmbibcr {
  d: path("M6 8h8a1.25 1.25 0 1 0-1.25-1.25M6 11h6m-6 3h10a1.25 1.25 0 1 0-1.25-1.25");
}

</style>
