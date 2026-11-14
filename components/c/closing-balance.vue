<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n13x6dbmu"/><path class="ue6__l6qt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:closing-balance" /></template>
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

.ue6__l6qt {
  d: path("M4.5 19A2.5 2.5 0 0 1 7 16.5h12.5M8 6.5h8M8 9.25h8M8.625 12h6.75a.625.625 0 0 1 .625.625a.625.625 0 0 1-.625.625h-6.75A.625.625 0 0 1 8 12.625A.625.625 0 0 1 8.625 12");
}

</style>
