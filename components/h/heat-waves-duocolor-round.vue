<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m88_si58t"/><path class="xua654byr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heat-waves-duocolor-round" /></template>
<style>
.m88_si58t {
  stroke-opacity: 0.4;
  d: path("M12 21q4-4.5 0-9t0-9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xua654byr {
  d: path("M6 21q4-4.5 0-9t0-9m12 18q4-4.5 0-9t0-9");
}

</style>
