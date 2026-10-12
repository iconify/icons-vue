<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qbn9ahbbt"/><path class="oik771vcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:autoplay-sharp" /></template>
<style>
.oik771vcr {
  d: path("m15.08 9.89l2.59 1.72l.58.39l-.58.39l-2.59 1.72l-.58.39v-5z");
}

.qbn9ahbbt {
  d: path("M2.75 6.75h18.5v10.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
