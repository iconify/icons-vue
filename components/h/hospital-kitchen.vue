<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="enzs1c_3x"/><path class="n0q0gac6b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hospital-kitchen" /></template>
<style>
.enzs1c_3x {
  d: path("M4 8v6.5c0 1.7 1.3 3 3 3h4.49m4.01-5.88V8m-13 0H17M5 8c0-2.5 2-3.5 4.75-3.5s4.75 1 4.75 3.5M9.75 4.5V2.75m-7.25 8H4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n0q0gac6b {
  fill: currentColor;
  d: path("M16.5 14.25h3v2.25h2.25v3H19.5v2.25h-3V19.5h-2.25v-3h2.25Z");
}

</style>
