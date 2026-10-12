<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bu__6tbem"/><path class="qc1w82bey"/><path class="lr6id3byi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cheetah-sharp" /></template>
<style>
.bu__6tbem {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 9l-.25-3.75V3.538l1.4.862L9.5 6l1.28-.4h2.44l1.28.4l2.85-1.6l1.4-.862V5.25L18.5 9l1.5 1.875V14.5l1 1.25l-1.75.25c-1.25 3.25-4 5-7.25 5s-6-1.75-7.25-5L3 15.75l1-1.25v-3.625z");
}

.lr6id3byi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 11.25h.01m5.49 0h.01");
}

.qc1w82bey {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.25 12.25l-.435 3.043L11 16.75m3.75-4.5l.435 3.043L13 16.75");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
