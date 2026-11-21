<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="f66c-0bag"/><path class="ej3l6xevc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bot-network-sharp" /></template>
<style>
.ej3l6xevc {
  d: path("M6 5L18 5L18 13L6 13ZM12 5L12 1M3 9L6 9M18 9L21 9M9 13L5 17M15 13L19 17M2 17L8 17L8 22L2 22ZM16 17L22 17L22 22L16 22Z");
}

.f66c-0bag {
  fill: currentColor;
  d: path("M11 9C11 9.5523 10.5523 10 10 10C9.4477 10 9 9.5523 9 9C9 8.4477 9.4477 8 10 8C10.5523 8 11 8.4477 11 9ZM15 9C15 9.5523 14.5523 10 14 10C13.4477 10 13 9.5523 13 9C13 8.4477 13.4477 8 14 8C14.5523 8 15 8.4477 15 9Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
