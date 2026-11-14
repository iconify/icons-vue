<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vl7bzrwxf"/><path class="rh_dnsbhp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:carriage-number" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rh_dnsbhp {
  d: path("M4.5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m11 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-6.75-11h6.5A1.75 1.75 0 0 1 17 9.25v2A1.75 1.75 0 0 1 15.25 13h-6.5A1.75 1.75 0 0 1 7 11.25v-2A1.75 1.75 0 0 1 8.75 7.5M10 10.25h4");
}

.vl7bzrwxf {
  d: path("M2.5 16.5V8C2.5 5 6 3.5 12 3.5S21.5 5 21.5 8v8.5Z");
}

</style>
