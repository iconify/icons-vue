<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="syxzvcbel"/><path class="g_vqk4b4w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:doormat" /></template>
<style>
.g_vqk4b4w {
  d: path("M10.516 9.5h4.268a1.5 1.5 0 0 1 1.393 2.057l-.8 2a1.5 1.5 0 0 1-1.393.943H9.716a1.5 1.5 0 0 1-1.393-2.057l.8-2a1.5 1.5 0 0 1 1.393-.943");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.syxzvcbel {
  d: path("M7.28 6.5h11.827a1.75 1.75 0 0 1 1.667 2.281l-2.386 7.5A1.75 1.75 0 0 1 16.72 17.5H4.893a1.75 1.75 0 0 1-1.667-2.281l2.386-7.5A1.75 1.75 0 0 1 7.28 6.5");
}

</style>
