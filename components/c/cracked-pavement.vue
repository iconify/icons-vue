<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fuv597b_w"/><path class="f04uoqbvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cracked-pavement" /></template>
<style>
.f04uoqbvy {
  d: path("m17.5 6l-1.75 4l2 3l-2.5 5");
}

.fuv597b_w {
  d: path("M7.313 6h11.854a1.75 1.75 0 0 1 1.68 2.24l-2.48 8.5A1.75 1.75 0 0 1 16.688 18H4.833a1.75 1.75 0 0 1-1.68-2.24l2.48-8.5A1.75 1.75 0 0 1 7.313 6m6.437 0l-3.5 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
