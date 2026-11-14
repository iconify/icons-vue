<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ti6l08b3y"/><path class="v4dm87blb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:diapers-pack" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ti6l08b3y {
  d: path("M7.375 5.5h9.25A4.375 4.375 0 0 1 21 9.875v6.25a4.375 4.375 0 0 1-4.375 4.375h-9.25A4.375 4.375 0 0 1 3 16.125v-6.25A4.375 4.375 0 0 1 7.375 5.5M15 5.5V3h3.5v2.5");
}

.v4dm87blb {
  d: path("M7.5 9.5h9V12q-2.5.5-3.25 4h-2.5Q10 12.5 7.5 12Z");
}

</style>
