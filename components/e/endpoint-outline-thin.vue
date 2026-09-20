<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wmhzb8pmw"/><path class="mplr9elex"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:endpoint-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mplr9elex {
  d: path("M15 18a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.wmhzb8pmw {
  d: path("m3 3 10 10");
}

</style>
