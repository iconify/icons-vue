<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pp7umkmgo"/><path class="fsnfx25hs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chapel" /></template>
<style>
.fsnfx25hs {
  d: path("M10 21.5v-3a2 2 0 0 1 4 0v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pp7umkmgo {
  d: path("M3.5 21.5V15L9 12.5V10l3-4l3 4v2.5l5.5 2.5v6.5ZM12 2v4m-2-2.25h4");
}

</style>
