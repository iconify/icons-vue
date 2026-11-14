<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e0ez1bc7e"/><path class="v7mfnnboa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:empty-nest" /></template>
<style>
.e0ez1bc7e {
  d: path("M2.5 8.5h19c0 6-4.5 9.5-9.5 9.5s-9.5-3.5-9.5-9.5M4 6l3.5 2.5M20 6l-3.5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v7mfnnboa {
  d: path("m6 11.5l3 2.75l3-2.75l3 2.75l3-2.75");
}

</style>
