<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="r779pvaqi"/><path class="e6vhfnovj"/><path class="e2c2s8bhf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:funicular-sharp" /></template>
<style>
.e2c2s8bhf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.75 21.25l18.5-8.75");
}

.e6vhfnovj {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 17.5h.01m7.99-3.78h.01");
}

.r779pvaqi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 10.75h5.5v-4H18v4.29l-.9.43l-11.2 5.29l-.9.43v-6.44zm5.5 0v3.37M18 9l3.25-1.54");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
