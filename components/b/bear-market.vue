<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p8u760b4u"/><path class="svkwq82ml"/><path class="p-xk61mdx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bear-market" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p-xk61mdx {
  d: path("M15.5 13.5h4v-4");
}

.p8u760b4u {
  d: path("M3.5 3v17.5H21");
}

.svkwq82ml {
  d: path("m7 5.5l4 5L14 8l5.5 5.5");
}

</style>
