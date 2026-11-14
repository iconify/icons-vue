<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cotuwjbzt"/><path class="zikstd9vo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fly" /></template>
<style>
.cotuwjbzt {
  d: path("M2.5 15a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m5 0a6 3.5 0 1 0 12 0a6 3.5 0 1 0-12 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zikstd9vo {
  d: path("M11.75 11.75C8 10 6.5 4 9 3s4 4 2.75 8.75M14 11.5c0-5 3.5-8.5 5.5-7s-1.5 6-5.5 7m-3.5 6.75L9.5 21m5.5-2.75L16 21");
}

</style>
