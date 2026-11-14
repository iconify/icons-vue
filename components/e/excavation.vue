<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w35o-vbyv"/><path class="an0yfct5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:excavation" /></template>
<style>
.an0yfct5l {
  d: path("m15.923 8.823l.541-.866a1.75 1.75 0 0 1 2.996.046l.505.865a1.75 1.75 0 0 1-1.512 2.632h-1.046a1.75 1.75 0 0 1-1.484-2.677");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w35o-vbyv {
  d: path("M2.5 11.5h3v7H13v-7h8.5");
}

</style>
