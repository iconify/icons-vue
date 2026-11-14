<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i29pb-bia"/><path class="efzdgs0lc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:glacier-glasses" /></template>
<style>
.efzdgs0lc {
  fill: currentColor;
  d: path("M4.25 8h6.5v4.5a3.25 3.25 0 0 1-3.25 3.25a3.25 3.25 0 0 1-3.25-3.25Zm9 0h6.5v4.5a3.25 3.25 0 0 1-3.25 3.25a3.25 3.25 0 0 1-3.25-3.25Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i29pb-bia {
  d: path("M2.5 8h19m-19 0v5.5L4.25 12M21.5 8v5.5L19.75 12");
}

</style>
