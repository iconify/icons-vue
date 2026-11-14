<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b8qg20bje"/><path class="gshz66n0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ambulance-side" /></template>
<style>
.b8qg20bje {
  d: path("M6 6h5a3.5 3.5 0 0 1 3.5 3.5v4A3.5 3.5 0 0 1 11 17H6a3.5 3.5 0 0 1-3.5-3.5v-4A3.5 3.5 0 0 1 6 6m8.5 3H18l3.5 3.5V17h-7Z");
}

.gshz66n0r {
  d: path("M5 18a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-7-9.5V14M6 11.25h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
