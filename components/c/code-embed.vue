<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s-_gubcwr"/><path class="gu5_5bcph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:code-embed" /></template>
<style>
.gu5_5bcph {
  d: path("m8 7.5l-2.25 3.25L8 14m3-6.5l2.25 3.25L11 14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s-_gubcwr {
  d: path("M6.5 2.5h6A3.5 3.5 0 0 1 16 6v9.5a3.5 3.5 0 0 1-3.5 3.5h-6A3.5 3.5 0 0 1 3 15.5V6a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
