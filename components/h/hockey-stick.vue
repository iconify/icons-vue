<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q0ybizbex"/><path class="pxyd8_r1u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hockey-stick" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pxyd8_r1u {
  d: path("m18.75 3l-9 13.5a2 2 0 0 1-1.66.9H3.75m5.5 2.45a2.75 1.35 0 1 0 5.5 0a2.75 1.35 0 1 0-5.5 0");
}

.q0ybizbex {
  d: path("m5.25 3l9 13.5a2 2 0 0 0 1.66.9h4.34");
}

</style>
