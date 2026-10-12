<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="sye52-btp"/><path class="nlrdmwb0k"/><path class="qd9cjrn4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ferry-boat" /></template>
<style>
.nlrdmwb0k {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 10.85h.01m3.99 0h.01m3.99 0h.01");
}

.qd9cjrn4u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12.5h18.5l-1.75 3.9a1.75 1.75 0 0 1-1.62 1.1H6.12a1.75 1.75 0 0 1-1.62-1.1Zm0 8.75c1.25 0 1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75s1.25.75 2.5.75s1.25-.75 2.5-.75");
}

.sye52-btp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.25 5.5V3.75a1 1 0 0 1 1-1h1.5a1 1 0 0 1 1 1V5.5Zm-9.5 7v-6a1 1 0 0 1 1-1h12.5a1 1 0 0 1 1 1v6Zm0-3.5h14.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
