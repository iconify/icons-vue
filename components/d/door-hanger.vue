<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="asypbef-w"/><path class="h9fie9u5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:door-hanger" /></template>
<style>
.asypbef-w {
  d: path("M4.5 2.5v19m8-19h3A3.5 3.5 0 0 1 19 6v12a3.5 3.5 0 0 1-3.5 3.5h-3A3.5 3.5 0 0 1 9 18V6a3.5 3.5 0 0 1 3.5-3.5");
}

.h9fie9u5w {
  d: path("M11.5 7.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m0 7.5h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
