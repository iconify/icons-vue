<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="hgpzqkfhu"/><path class="atv66_b1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ceiling-medallion" /></template>
<style>
.atv66_b1j {
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.hgpzqkfhu {
  d: path("M17.5 12A2.25 2.25 0 0 0 16 8a2.25 2.25 0 0 0-4-1.5A2.25 2.25 0 0 0 8 8a2.25 2.25 0 0 0-1.5 4A2.25 2.25 0 0 0 8 16a2.25 2.25 0 0 0 4 1.5a2.25 2.25 0 0 0 4-1.5a2.25 2.25 0 0 0 1.5-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdgu3ybil {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
