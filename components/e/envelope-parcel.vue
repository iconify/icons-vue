<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ex_-tdmpb"/><path class="tvgwi4boa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:envelope-parcel" /></template>
<style>
.ex_-tdmpb {
  d: path("M7 6h10a3.5 3.5 0 0 1 3.5 3.5v5A3.5 3.5 0 0 1 17 18H7a3.5 3.5 0 0 1-3.5-3.5v-5A3.5 3.5 0 0 1 7 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tvgwi4boa {
  d: path("m3.5 8l8.5 6l8.5-6");
}

</style>
