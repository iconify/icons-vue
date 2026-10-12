<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="k1-68oc6f"/><path class="i2c8mef7s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crocodile-sharp" /></template>
<style>
.i2c8mef7s {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 10.5h.01");
}

.k1-68oc6f {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.75 11.5l4.5-1l.417-1.25h2.166l.417 1.25l.75-.75l.75.75l.75.75l.75-.75l.75-.75l.75.75C18 10.5 19.5 12 21 13.75l.233.35H20.8l-4.05.15l1 2l.333.75h-3.104l.321-.75l.2-.5l-.5-1.5h-4.75l-.5 2l-.167.75H6.864l.536-.75l1.1-2H8c-1.75-.25-3.25-.5-4.25-.75L3 13.2v-1.475z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
