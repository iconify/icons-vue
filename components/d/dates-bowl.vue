<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ymqdpcgnd"/><path class="mz2s1mb6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dates-bowl" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mz2s1mb6a {
  d: path("M10 8.25a2 4.25 0 1 0 4 0a2 4.25 0 1 0-4 0M3.5 9.5a2 3.5 0 1 0 4 0a2 3.5 0 1 0-4 0m13 0a2 3.5 0 1 0 4 0a2 3.5 0 1 0-4 0");
}

.ymqdpcgnd {
  d: path("M2.5 12.5h19c0 4.5-4 7.5-9.5 7.5s-9.5-3-9.5-7.5");
}

</style>
