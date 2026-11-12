<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s_mr-hbpj"/><path class="yj0yf9o2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:alt-arrow-up-line-duotone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s_mr-hbpj {
  d: path("M19 15L12 9L5 15");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.yj0yf9o2f {
  d: path("M8.5 12L12 9L19 15");
}

</style>
