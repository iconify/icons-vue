<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="pg952fx-z"/><path class="q-qqnwbyu"/><path class="ku9kybbms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:goat-farm-sharp" /></template>
<style>
.ku9kybbms {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 21.25h18.5");
}

.pg952fx-z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 10.25h7.75l.33-.94l1.09-3.12l.33-.94l.97-.24l.06-.02l.97-.24l.68.73l1.89 2.04l.68.73l-.5.63l-.5.62l-.98-.18l-.79-.14L17 9l-.18.98l-.64 3.54l-.18.98H5v-4.25zm.5 4.25v3.75M9 14.5v3.75m3.5-3.75v3.75m2.25-3.75v3.75M16.25 5l-.375-1.5L14 2.75m6 6.75l-.5 1.75M5 10.5l-1.25-2");
}

.q-qqnwbyu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.75 6.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
