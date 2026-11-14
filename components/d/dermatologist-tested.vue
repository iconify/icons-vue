<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xxwynxb5b"/><path class="gbg-obbdc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dermatologist-tested" /></template>
<style>
.gbg-obbdc {
  d: path("m8 12.25l3 3l5-5.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xxwynxb5b {
  d: path("M4.5 5C8 5 10 4 12 2.5C14 4 16 5 19.5 5v6c0 5-3 8.5-7.5 10.5c-4.5-2-7.5-5.5-7.5-10.5Z");
}

</style>
