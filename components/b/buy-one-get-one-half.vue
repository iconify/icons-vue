<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jb65mlb_w"/><path class="nvkr7_l_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:buy-one-get-one-half" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jb65mlb_w {
  d: path("M4.25 7h5A1.75 1.75 0 0 1 11 8.75v8.5A1.75 1.75 0 0 1 9.25 19h-5a1.75 1.75 0 0 1-1.75-1.75v-8.5A1.75 1.75 0 0 1 4.25 7m10.5 0h5a1.75 1.75 0 0 1 1.75 1.75v8.5A1.75 1.75 0 0 1 19.75 19h-5A1.75 1.75 0 0 1 13 17.25v-8.5A1.75 1.75 0 0 1 14.75 7M2.5 10H11m2 0h8.5");
}

.nvkr7_l_a {
  fill: currentColor;
  d: path("M17.121 18.5H19.5A1.5 1.5 0 0 0 21 17v-2.379a1.5 1.5 0 0 0-2.561-1.06l-2.378 2.378a1.5 1.5 0 0 0 1.06 2.561");
}

</style>
