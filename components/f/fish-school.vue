<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="nkl0rzbqa"/><path class="li71qpe7b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fish-school" /></template>
<style>
.li71qpe7b {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 11.5h.01");
}

.nkl0rzbqa {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.5 4.75l1.75 1.5q3-3.2 6 0q-3 3.2-6 0L4.5 7.75Zm0 11.5l1.75 1.5q3-3.2 6 0q-3 3.2-6 0l-1.75 1.5Zm4-5.75l1.75 1.5q4.5-4.8 9 0q-4.5 4.8-9 0L8.5 13.5Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
