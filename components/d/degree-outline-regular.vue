<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ez875nbbx"/><path class="n30k87bda"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:degree-outline-regular" /></template>
<style>
.ez875nbbx {
  d: path("m2 8 4 -4h12l4 4 -4 4H6Z");
}

.n30k87bda {
  d: path("M5 16a2 2 0 0 0 0 4h14a2 2 0 0 0 0 -4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
