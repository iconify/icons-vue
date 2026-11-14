<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n13x6dbmu"/><path class="ws4w22b6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:comic-book" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n13x6dbmu {
  d: path("M4.5 19V5A2.5 2.5 0 0 1 7 2.5h12.5v19H7A2.5 2.5 0 0 1 4.5 19");
}

.ws4w22b6g {
  d: path("M4.5 19A2.5 2.5 0 0 1 7 16.5h12.5M10 5.5h5.5A1.5 1.5 0 0 1 17 7v3a1.5 1.5 0 0 1-1.5 1.5H12L10 13v-1.5A1.5 1.5 0 0 1 8.5 10V7A1.5 1.5 0 0 1 10 5.5");
}

</style>
