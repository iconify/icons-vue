<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gllv8yijc"/><path class="ie_rp7b5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:home-contents" /></template>
<style>
.gllv8yijc {
  d: path("M5 13v-3a2.5 2.5 0 0 1 2.5-2.5h9A2.5 2.5 0 0 1 19 10v3");
}

.ie_rp7b5m {
  d: path("M2.5 14.5A1.5 1.5 0 0 1 5 13v3.5h14V13a1.5 1.5 0 0 1 2.5 1.5v4h-19Zm2.5 4v2m14-2v2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
