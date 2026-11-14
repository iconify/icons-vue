<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m7szh0f-l"/><path class="gu5_5bcph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-embed" /></template>
<style>
.gu5_5bcph {
  d: path("m8 7.5l-2.25 3.25L8 14m3-6.5l2.25 3.25L11 14");
}

.m7szh0f-l {
  d: path("M3 2.5h13V19H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
