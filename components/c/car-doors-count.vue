<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qsr6q-bdl"/><path class="hxe-6bbcw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-doors-count" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hxe-6bbcw {
  d: path("M4.5 15a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-.5-11v6.25M19.75 16l-3.5 5H22m-1.25-3v4");
}

.qsr6q-bdl {
  d: path("M2.5 13v-3A1.5 1.5 0 0 1 4 8.5h1.5L8 5c.4-.6 1-1 1.75-1H14c.75 0 1.3.4 1.75 1L18 8.5h1.5A1.5 1.5 0 0 1 21 10v3Z");
}

</style>
