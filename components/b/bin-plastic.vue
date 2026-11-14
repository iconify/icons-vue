<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fr7h0jopz"/><path class="caaa9kgvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bin-plastic" /></template>
<style>
.caaa9kgvp {
  d: path("M11 8.5h2v2l1.5 2V18h-5v-5.5l1.5-2Z");
}

.fr7h0jopz {
  d: path("M3.5 5.5h17m-11 0v-2h5v2M5 5.5L6.5 21h11L19 5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
