<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lnz9ryb0q"/><path class="z65c2carw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-carrier" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lnz9ryb0q {
  d: path("M15.25 9H2.5v7h19v-4L20 10h-2v6M2.75 9V7.25l1.5-2h2l1.5 2V9m2.5 0V7.25l1.5-2h2l1.5 2V9");
}

.z65c2carw {
  d: path("M4.25 17.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m12.5 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
