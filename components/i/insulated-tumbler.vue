<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5-pdybga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:insulated-tumbler" /></template>
<style>
.f5-pdybga {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 4.5h10A1.5 1.5 0 0 1 18.5 6A1.5 1.5 0 0 1 17 7.5H7A1.5 1.5 0 0 1 5.5 6A1.5 1.5 0 0 1 7 4.5m3 3h4a3.5 3.5 0 0 1 3.5 3.5v7a3.5 3.5 0 0 1-3.5 3.5h-4A3.5 3.5 0 0 1 6.5 18v-7A3.5 3.5 0 0 1 10 7.5m4-3L16.5 2m-7 8.5v8");
}

</style>
