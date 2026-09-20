<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j2r1pso3k"/><path class="atrqakbcy"/><path class="sxlwlmkmh"/><path class="h-_fm4bbo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-right-duotone-thin" /></template>
<style>
.atrqakbcy {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 7 5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h-_fm4bbo {
  d: path("m15 7 5 5 -5 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j2r1pso3k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 12h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sxlwlmkmh {
  d: path("M4 12h16");
}

</style>
