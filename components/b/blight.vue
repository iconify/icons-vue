<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yjj9rmb_c"/><path class="du2fg78ji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blight" /></template>
<style>
.du2fg78ji {
  d: path("M9.25 12.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m4-4a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yjj9rmb_c {
  d: path("M3 21C3 10.5 10.5 3 21 3c0 5-1 8-2.5 10l-2.5-.5l.5 3l-3 .25v2.75C10 20.5 6.5 21 3 21m0 0l5-5");
}

</style>
