<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x8sqkdfzp"/><path class="l0ibohb7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-unordered-duocolor" /></template>
<style>
.l0ibohb7c {
  d: path("M9 7h10M9 12h10M9 17h10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x8sqkdfzp {
  stroke-opacity: 0.4;
  d: path("M5 7h.01M5 12h.01M5 17h.01");
}

</style>
