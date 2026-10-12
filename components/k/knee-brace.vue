<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="s9ieibcwy"/><path class="ty7uucb9j"/><path class="g1w5unbbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:knee-brace" /></template>
<style>
.g1w5unbbn {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.24 4.6l-3.62 6.57m6.86 7.68l-5.6-4.98");
}

.s9ieibcwy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.45 3.37L15.87 8a3.5 3.5 0 0 1 1.17 6.84l-4.8 5.4a3 3 0 0 1-4.48-3.98l3.5-3.94l-6.71-3.69a3 3 0 0 1 2.9-5.26");
}

.ty7uucb9j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 11.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
