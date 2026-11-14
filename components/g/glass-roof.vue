<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i7wiwtbvv"/><path class="i46sb_buq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:glass-roof" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i46sb_buq {
  d: path("M2.5 13v6h15v-6m-6-8l-4 8m9-8l-4 8m-8-4h15");
}

.i7wiwtbvv {
  d: path("m3.585 10.829l2.5-5A1.5 1.5 0 0 1 7.427 5h11.646a1.5 1.5 0 0 1 1.342 2.171l-2.5 5a1.5 1.5 0 0 1-1.342.829H4.927a1.5 1.5 0 0 1-1.342-2.171");
}

</style>
