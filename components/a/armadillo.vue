<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kqmfg7bsx"/><path class="izdobts9k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:armadillo" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.izdobts9k {
  d: path("M8.75 12.5c-1.5 0-3 .75-4.25 2l-1.25 1.25c-.4.4-.15.75.35.75h4.9Zm-1.85.25l-.65-2.5m5.5.75v5.5m2.5-5.5v5.5M17.4 15c1.5.75 2.85 1.75 3.85 3.25m-11-1.75v2.75m5.5-2.75v2.75");
}

.kqmfg7bsx {
  d: path("M8.5 16.5c0-5.5 1.75-9.25 4.5-9.25s4.5 3.75 4.5 9.25Z");
}

</style>
