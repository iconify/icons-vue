<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s19aowben"/><path class="f6p-2g58b"/><path class="o8ymreppw"/><path class="hjhjwb4fd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:list-arrow-up-minimalistic-line-duotone" /></template>
<style>
.f6p-2g58b {
  d: path("M11 11L3 11");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.hjhjwb4fd {
  stroke-linejoin: round;
  d: path("M20 11.5L17.5 9L15 11.5M17.5 9V17");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o8ymreppw {
  d: path("M12 16H3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.s19aowben {
  d: path("M20 6L3 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
