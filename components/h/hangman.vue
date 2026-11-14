<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jesvjub2n"/><path class="oqza4kjgc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hangman" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jesvjub2n {
  d: path("M4.5 21.5h10m-6.5 0v-18h8.5V6");
}

.oqza4kjgc {
  d: path("M14 8.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m2.5 2.5v5m-3-3h6m-3 3L14 19.5m2.5-3.5l2.5 3.5");
}

</style>
