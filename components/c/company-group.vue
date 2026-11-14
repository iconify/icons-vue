<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="exxvlzbym"/><path class="m9fy4_0ed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:company-group" /></template>
<style>
.exxvlzbym {
  d: path("M2.5 21V10h5.25V3h8.5v10h5.25v8Zm5.25-11v11m8.5-8v8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m9fy4_0ed {
  d: path("M10.5 21v-4h3v4");
}

</style>
