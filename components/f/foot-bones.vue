<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="axpwcgb8p"/><path class="s42c9-blb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:foot-bones" /></template>
<style>
.axpwcgb8p {
  d: path("M8 21.5c-2 0-3-2-2.75-4.5c.25-3-.75-6-.25-9c.5-3.5 3-5.5 6.5-5.5s6.5 1.5 7 5c.5 3-1.5 5.5-2 8.5S15 21.5 12 21.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s42c9-blb {
  d: path("M8.5 18a2.5 2 0 1 0 5 0a2.5 2 0 1 0-5 0m0-3.5l-.75-5m0-1.5L7.5 5.5m3.75 9v-5m0-1.5V5M14 14.5l1-4.75m.25-1.5L15.5 6");
}

</style>
