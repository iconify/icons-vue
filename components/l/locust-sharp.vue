<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="vjc_8yb4k"/><path class="eg8lrn8bb"/><path class="r776bxbjn"/><path class="p85-dzbqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:locust-sharp" /></template>
<style>
.eg8lrn8bb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15 11.5C13.5 9.25 8.5 7.25 3.75 7.75l-2.391.22L3.45 9.15L7.5 11.5Z");
}

.p85-dzbqh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 15.5L9.5 20l-4.5.25M18.75 9.9l.358-2.865L21 5.9");
}

.r776bxbjn {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.75 12.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vjc_8yb4k {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.52 12.53l.46-.31L6 11.5h9.5l.94-.82l.12-.11l.94-.82l1.22.28l.81.19l1.22.28l.19 1.24l.12.77l.19 1.24l-.99.77l-.27.21l-.99.77h-3.25q-1.25 0-2.5-.11l-6-.53L6 14.75l-1.07-.64l-.36-.22l-1.07-.64z");
}

</style>
