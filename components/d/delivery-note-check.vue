<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e1bkw0jxi"/><path class="mwiflzbfl"/><path class="pmmw6ndeg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:delivery-note-check" /></template>
<style>
.e1bkw0jxi {
  d: path("M4.829 7.226q-.017-.074-.023-.149q-.006-.076 0-.152q.005-.075.022-.149t.045-.144t.066-.136t.086-.125t.104-.11t.119-.093l3-2Q8.5 4 8.803 4h9.394q.08 0 .159.013t.155.037q.076.026.147.062t.135.085q.064.047.12.105t.102.122q.046.066.081.138t.058.148q.023.077.034.156t.009.159t-.017.159q-.014.078-.041.154q-.027.075-.066.145t-.088.133t-.108.117q-.058.055-.125.099l-3 2Q15.5 8 15.197 8h-1.651m.054 0h1.9v13.5h-13V8h1.9");
}

.mwiflzbfl {
  d: path("m15.945 7.703l4-2.667a1 1 0 0 1 1.555.833v11.096a1 1 0 0 1-.445.832l-4 2.667a1 1 0 0 1-1.555-.833V8.535a1 1 0 0 1 .445-.832ZM13.5 14.8v4.7h-9v-4.7");
}

.pmmw6ndeg {
  d: path("m6 15.25l1.25 1.25l1.47-1.68m1.53.18H12m-4.75-5h3.5v2h-3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
