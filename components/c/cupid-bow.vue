<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f6nb7ob2z"/><path class="s1ffzhgum"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cupid-bow" /></template>
<style>
.f6nb7ob2z {
  d: path("M9 3q8 9 0 18M9 3v18m-6-9h13.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s1ffzhgum {
  d: path("m21.5 12l-3.75-3.5A2 2 0 0 0 16.5 12a2 2 0 0 0 1.25 3.5Z");
}

</style>
