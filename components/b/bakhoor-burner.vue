<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v0j4itbml"/><path class="rru1ybbwc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bakhoor-burner" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rru1ybbwc {
  d: path("M9.5 18.25L8 21.5h8l-1.5-3.25M5.5 13a6.5 5 0 0 1 13 0M12 5.25c-2.25-.75 2.25-2.25 0-3");
}

.v0j4itbml {
  d: path("M4 13h16a8 5.5 0 0 1-16 0");
}

</style>
