<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="womf36imi"/><path class="trq_-4b9z"/><path class="utcsptk8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-documents" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.trq_-4b9z {
  d: path("M9 5.5h6l5 5v9a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2v-12a2 2 0 0 1 2-2");
}

.utcsptk8o {
  d: path("M15 5.5v3a2 2 0 0 0 2 2h3M9.5 18v-2.25l1.5-.5l1.25-2H15l1.5 2l1.5.5V18h-1.25a1.25 1.25 0 0 0-2.5 0h-1.5a1.25 1.25 0 0 0-2.5 0Z");
}

.womf36imi {
  d: path("M4 18.5v-14a2 2 0 0 1 2-2h7");
}

</style>
