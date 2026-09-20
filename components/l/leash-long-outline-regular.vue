<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ttbqujc9j"/><path class="m1k1s7nte"/><path class="gyi-tobvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:leash-long-outline-regular" /></template>
<style>
.gyi-tobvb {
  d: path("M20 5v14");
}

.m1k1s7nte {
  d: path("M10 12h10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ttbqujc9j {
  d: path("M7.69 8.37a4 4 0 1 1 -3.38 0");
}

</style>
