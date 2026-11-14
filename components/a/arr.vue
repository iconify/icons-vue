<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s4p2nsbox"/><path class="emnqn2bgt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arr" /></template>
<style>
.emnqn2bgt {
  d: path("M6.75 2.5L9 3.5L7.75 6m6.5 3.25C14 8.5 13.2 8 12 8c-1.4 0-2.25.75-2.25 1.75c0 2.25 4.5 1.5 4.5 4.25c0 1.1-.95 2-2.25 2c-1.2 0-2.1-.6-2.25-1.5M12 6.25V8m0 8v1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s4p2nsbox {
  d: path("M18.364 5.636a9 9 0 1 1-9.442-2.093");
}

</style>
