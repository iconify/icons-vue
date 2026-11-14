<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="we9dtqb6t"/><path class="lacsvmmby"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fitness-band" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lacsvmmby {
  d: path("M8.5 12h2l1.25-2.5l1.25 5l1.25-2.5h1.25");
}

.we9dtqb6t {
  d: path("M9.875 6.5h4.25a4.375 4.375 0 0 1 4.375 4.375v2.25a4.375 4.375 0 0 1-4.375 4.375h-4.25A4.375 4.375 0 0 1 5.5 13.125v-2.25A4.375 4.375 0 0 1 9.875 6.5M8.5 2.5v4m7-4v4m-7 11v4m7-4v4");
}

</style>
