<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="foylt9ial"/><path class="row4r_b0n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lane-arrow-right" /></template>
<style>
.foylt9ial {
  d: path("M7 20v-8.5a3 3 0 0 1 3-3h9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.row4r_b0n {
  d: path("M15.25 4.75L19 8.5l-3.75 3.75");
}

</style>
