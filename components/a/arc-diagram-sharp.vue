<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="h6fn9q-1n"/><path class="libckgbih"/><path class="sy16llhju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arc-diagram-sharp" /></template>
<style>
.h6fn9q-1n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 13.75a5.5 5.5 0 0 1 11 0");
}

.libckgbih {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 13.75a5.5 5.5 0 0 1 11 0");
}

.sy16llhju {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 17h.01M9 17h.01M15 17h.01M20 17h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
