<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fn-vlqbay"/><path class="ad7ucbnxe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dino-footprint" /></template>
<style>
.ad7ucbnxe {
  d: path("M10 15.5q2-1.5 4 0");
}

.fn-vlqbay {
  d: path("M8 16.75L3 9.5l-.5-3.75l3 2l4.75 5v-6L12 3.25l1.75 3.5v6l4.75-5l3-2L21 9.5l-5 7.25a4 4 0 0 1-8 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
