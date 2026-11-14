<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mly3sybza"/><path class="h4dgr8bcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:air-fryer" /></template>
<style>
.h4dgr8bcl {
  d: path("M9 9.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0M4 15h16m-10 3h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mly3sybza {
  d: path("M4 21.25V9a8 6.5 0 0 1 16 0v12.25Z");
}

</style>
