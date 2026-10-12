<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="bv79b0yvy"/><path class="u36aqldlt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hanger-tag" /></template>
<style>
.bv79b0yvy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 4.5A1.75 1.75 0 1 1 12 6.25V7m0 0l7.9 5a1 1 0 0 1-.55 1.85H4.65A1 1 0 0 1 4.1 12Zm2.05 10.75l1.65-1.5q.55-.5 1.1 0l1.65 1.5q.55.5.55 1.25v1.5q0 .75-.75.75h-4q-.75 0-.75-.75V19q0-.75.55-1.25");
}

.u36aqldlt {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.25 18.5h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
