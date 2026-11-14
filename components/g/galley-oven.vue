<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sb0l6tjkv"/><path class="q3fi_ebxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:galley-oven" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q3fi_ebxt {
  d: path("M9.125 11.5h5.75a2.625 2.625 0 0 1 2.625 2.625v.75a2.625 2.625 0 0 1-2.625 2.625h-5.75A2.625 2.625 0 0 1 6.5 14.875v-.75A2.625 2.625 0 0 1 9.125 11.5M7 5.75h.01m3.49 0h.01");
}

.sb0l6tjkv {
  d: path("M6.875 3h10.25A4.375 4.375 0 0 1 21.5 7.375v8.75a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 16.125v-8.75A4.375 4.375 0 0 1 6.875 3M2.5 8.5h19");
}

</style>
