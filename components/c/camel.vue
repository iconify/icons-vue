<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="d9gn99bok"/><path class="zdidvox5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:camel" /></template>
<style>
.d9gn99bok {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 14.25C3.75 9.75 6 6.5 9 6.5c2.5 0 3.75 2.25 4.75 4.75l2.25-4c.4-.7 1.1-1 1.9-1h1.6A1.75 1.75 0 0 1 21.25 8a1 1 0 0 1-1 1h-1.5l-2.25 5.5c-.5.75-1.5 1.25-2.5 1.25H5.25a1.5 1.5 0 0 1-1.5-1.5m2 1.5v5.5m2.5-5.5v5.5m4.75-5.5v5.5M15.5 15l.25 6.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zdidvox5x {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.25 8.5h.01");
}

</style>
