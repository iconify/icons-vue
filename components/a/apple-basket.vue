<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="afib-ccvw"/><path class="pcw63tb9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:apple-basket" /></template>
<style>
.afib-ccvw {
  d: path("M3.875 12h16.25a1.375 1.375 0 0 1 1.375 1.375a1.375 1.375 0 0 1-1.375 1.375H3.875A1.375 1.375 0 0 1 2.5 13.375A1.375 1.375 0 0 1 3.875 12M4 14.75l1.75 5.75h12.5L20 14.75M10.25 12a3.5 3.5 0 1 1 3.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pcw63tb9c {
  d: path("M3 12a3.5 3.5 0 0 1 5.5-2.75M21 12a3.5 3.5 0 0 0-5.5-2.75M12 5.5Q12.25 4 13.5 3");
}

</style>
