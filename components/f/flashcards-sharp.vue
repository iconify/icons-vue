<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ozsb_0bmw"/><path class="bw0-gn9vf"/><path class="pfifjrafa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flashcards-sharp" /></template>
<style>
.bw0-gn9vf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 3.75h14v14M7.6 11.9a2.5 2.5 0 1 1 3.4 2.35l-1 .417v1.583");
}

.ozsb_0bmw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 6.75h14.5v14.5H2.75z");
}

.pfifjrafa {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 18.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
