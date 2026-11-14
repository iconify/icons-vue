<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ilh6fgb2t"/><path class="fwiik4b1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flying-fish" /></template>
<style>
.fwiik4b1o {
  d: path("m9 8.25l6.5-4.75L13 9m-6.5 2h.01M3 19q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ilh6fgb2t {
  d: path("M4 11c3-4 8.5-4 11.5 0l5-3.5v7l-5-3.5c-3 4-8.5 4-11.5 0");
}

</style>
