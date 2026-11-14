<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="in88odobq"/><path class="p2gj5_nrz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cloud-shield" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.in88odobq {
  d: path("M6.5 19a4.5 4.5 0 0 1 0-9a5.5 5.5 0 0 1 11 1a4 4 0 0 1 0 8Z");
}

.p2gj5_nrz {
  d: path("m12 9.5l3 1.25v2c0 1.75-1.25 2.75-3 3.25c-1.75-.5-3-1.5-3-3.25v-2Z");
}

</style>
