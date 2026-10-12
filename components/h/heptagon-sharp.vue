<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="vklfbv4rs"/><path class="yo_hj2bgd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:heptagon-sharp" /></template>
<style>
.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vklfbv4rs {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.58 3.41l4.47 2.15l1.57.76l.39 1.71l1.11 4.83l.39 1.71l-1.1 1.37l-3.09 3.88l-1.09 1.36H7.77l-1.09-1.36l-3.09-3.88l-1.1-1.37l.39-1.71l1.11-4.83l.39-1.71l1.57-.76l4.47-2.15L12 2.65z");
}

.yo_hj2bgd {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12.4h.01");
}

</style>
