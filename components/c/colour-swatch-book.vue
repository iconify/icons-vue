<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="an2p2cbcg"/><path class="p2luxou3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:colour-swatch-book" /></template>
<style>
.an2p2cbcg {
  d: path("M12 6c-2-1.5-6-2-9.5-1.5v14C6 18 10 18.5 12 20c2-1.5 6-2 9.5-1.5v-14C18 4 14 4.5 12 6m0 0v14M5.25 9.5h4m-4 4h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p2luxou3x {
  d: path("M16.25 9h1a1.5 1.5 0 0 1 1.5 1.5v2a1.5 1.5 0 0 1-1.5 1.5h-1a1.5 1.5 0 0 1-1.5-1.5v-2a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
