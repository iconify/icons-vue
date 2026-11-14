<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xy-qvi6_u"/><path class="v1mpasbmy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bush-baby" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v1mpasbmy {
  d: path("M6 9.5c-2.5-2.5-2.5-7 .25-7C8.75 2.5 9 5.5 7.5 8M18 9.5c2.5-2.5 2.5-7-.25-7c-2.5 0-2.75 3-1.25 5.5M7 14a2 2 0 1 0 4 0a2 2 0 1 0-4 0m6 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.xy-qvi6_u {
  d: path("M4.5 14a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0");
}

</style>
