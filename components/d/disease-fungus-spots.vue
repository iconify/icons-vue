<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f-uut-art"/><path class="tua4bbsnk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:disease-fungus-spots" /></template>
<style>
.f-uut-art {
  d: path("M3.5 20.5C2 8 8 2 20.5 3.5C22 16 16 22 3.5 20.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tua4bbsnk {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m5-4.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-8.75 9a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
