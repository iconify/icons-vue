<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p2ciopbql"/><path class="zbnoncc8l"/><path class="si7xw1b6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:brainwave-eeg" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p2ciopbql {
  d: path("M2.5 7H5l1.5-3l2 6L10 7h11.5");
}

.si7xw1b6h {
  d: path("M2.5 17H12l1.5-2.5l2 5L17 17h4.5");
}

.zbnoncc8l {
  d: path("M2.5 12H8l1.5-3l2 6l1.5-3h8.5");
}

</style>
