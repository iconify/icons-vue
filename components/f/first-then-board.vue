<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pmmtszb0r"/><path class="uu-1h2iim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:first-then-board" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pmmtszb0r {
  d: path("M6 10h1a3.5 3.5 0 0 1 3.5 3.5v4A3.5 3.5 0 0 1 7 21H6a3.5 3.5 0 0 1-3.5-3.5v-4A3.5 3.5 0 0 1 6 10m11 0h1a3.5 3.5 0 0 1 3.5 3.5v4A3.5 3.5 0 0 1 18 21h-1a3.5 3.5 0 0 1-3.5-3.5v-4A3.5 3.5 0 0 1 17 10M5 5h13.5m-2-2l2 2l-2 2");
}

.uu-1h2iim {
  d: path("M4.75 15.75L6.5 17.5l2.25-3.75m9.125.375l.03.071a1.33 1.33 0 0 0 1.22.804a.265.265 0 0 1 .147.485l-.022.015a1.235 1.235 0 0 0-.502 1.367l.004.016a.331.331 0 0 1-.502.367a1.35 1.35 0 0 0-1.5 0a.331.331 0 0 1-.502-.367l.004-.016a1.235 1.235 0 0 0-.502-1.367l-.022-.015a.265.265 0 0 1 .147-.485a1.33 1.33 0 0 0 1.22-.804l.03-.071a.408.408 0 0 1 .75 0");
}

</style>
