<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c2mtqwbnw"/><path class="ox397cb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-left-right-duotone" /></template>
<style>
.c2mtqwbnw {
  stroke-opacity: 0.4;
  d: path("M21 6L3 6M6 3L3 6L6 9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ox397cb9x {
  d: path("M3 18L21 18M18 15L21 18L18 21");
}

</style>
