<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a9r_v3b3b"/><path class="okohc-b1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chewable-tablet" /></template>
<style>
.a9r_v3b3b {
  d: path("M15.25 3.25a8 8 0 1 0 4.25 4.5a3.5 3.5 0 0 1-4.25-4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.okohc-b1j {
  d: path("M4 10.5v3a8 8 0 0 0 16 0v-3");
}

</style>
