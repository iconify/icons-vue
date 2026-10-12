<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v2177xb3m"/><path class="vjoucgx_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrow-curve-left" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v2177xb3m {
  d: path("M20.25 18.75c0-7.75-3.75-12.25-7.5-12.25s-6 4-6 9.25");
}

.vjoucgx_w {
  d: path("m2.75 11.75l4 4l4-4");
}

</style>
