<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aml2qxlgf"/><path class="kyds73bje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cat-cave" /></template>
<style>
.aml2qxlgf {
  d: path("M3.5 18.5c0-10 3-15 8.5-15s8.5 5 8.5 15m-18 0h19v3h-19Z");
}

.kyds73bje {
  d: path("M8 18.5V14a4 4 0 0 1 8 0v4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
