<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ua36h_b_w"/><path class="u7n-gewij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:billet" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u7n-gewij {
  d: path("M3 12h6.5l11-7m-11 7v6.5");
}

.ua36h_b_w {
  d: path("m3 12l11-7h6.5v6.5l-11 7H3Z");
}

</style>
