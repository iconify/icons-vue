<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oq2nkbb8e"/><path class="o2te4sjwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:line-dry" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o2te4sjwn {
  d: path("M9.5 3.5L5.75 5.75L7 9.25l1.5-.5v8.75h7V8.75l1.5.5l1.25-3.5L14.5 3.5q-2.5 2.5-5 0");
}

.oq2nkbb8e {
  d: path("M3 20.5v-17h18v17");
}

</style>
