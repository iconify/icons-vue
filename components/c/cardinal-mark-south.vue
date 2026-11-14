<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hy61e7b6z"/><path class="wx6op9oyi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cardinal-mark-south" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hy61e7b6z {
  d: path("M9 3.5h6l-3 4Zm0 4h6L12 11v2.5M7.25 19L9 13.5h6l1.75 5.5");
}

.wx6op9oyi {
  d: path("M2.5 19q2.375-1.5 4.75 0T12 19t4.75 0t4.75 0");
}

</style>
