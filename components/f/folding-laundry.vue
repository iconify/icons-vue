<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gh6affb3j"/><path class="ewhwfkqsh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:folding-laundry" /></template>
<style>
.ewhwfkqsh {
  d: path("m18.5 13.5l2 2l-2 2");
}

.gh6affb3j {
  d: path("M17 11.13V9.5l2.5 1l1.5-4l-5.5-3q-3.5 3-7 0L3 6.5l1.5 4l2.5-1v11h5.17m2.83 1V19a3.5 3.5 0 0 1 3.5-3.5h2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
