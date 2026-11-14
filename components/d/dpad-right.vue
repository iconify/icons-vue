<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g8r5xcmjw"/><path class="sk1vw_bju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dpad-right" /></template>
<style>
.g8r5xcmjw {
  d: path("M10.75 3h2.5A1.75 1.75 0 0 1 15 4.75v2.5A1.75 1.75 0 0 0 16.75 9h2.5A1.75 1.75 0 0 1 21 10.75v2.5A1.75 1.75 0 0 1 19.25 15h-2.5A1.75 1.75 0 0 0 15 16.75v2.5A1.75 1.75 0 0 1 13.25 21h-2.5A1.75 1.75 0 0 1 9 19.25v-2.5A1.75 1.75 0 0 0 7.25 15h-2.5A1.75 1.75 0 0 1 3 13.25v-2.5A1.75 1.75 0 0 1 4.75 9h2.5A1.75 1.75 0 0 0 9 7.25v-2.5A1.75 1.75 0 0 1 10.75 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sk1vw_bju {
  fill: currentColor;
  d: path("M16.75 9h2.5A1.75 1.75 0 0 1 21 10.75v2.5A1.75 1.75 0 0 1 19.25 15h-2.5A1.75 1.75 0 0 1 15 13.25v-2.5A1.75 1.75 0 0 1 16.75 9");
}

</style>
