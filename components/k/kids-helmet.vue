<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qwbbkj8ev"/><path class="r6lb9njed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kids-helmet" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qwbbkj8ev {
  d: path("M2.5 14c0-5.5 4-9 9.5-9s9.5 3.5 9.5 8L18 14Z");
}

.r6lb9njed {
  d: path("M7.5 8.25c2.5-1 6.5-1 9 .25M7 14l4 5.5l3.5-5.5");
}

</style>
