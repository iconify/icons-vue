<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="re-oy2-cw"/><path class="uwb_34brr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:join-visit" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.re-oy2-cw {
  d: path("M6.875 4.5h3.25A4.375 4.375 0 0 1 14.5 8.875v.75A4.375 4.375 0 0 1 10.125 14h-3.25A4.375 4.375 0 0 1 2.5 9.625v-.75A4.375 4.375 0 0 1 6.875 4.5");
}

.uwb_34brr {
  d: path("M15.35 7.49L17 6.5a1.651 1.651 0 0 1 2.5 1.415v2.67A1.651 1.651 0 0 1 17 12l-1.65-.99a1.75 1.75 0 0 1-.85-1.501v-.518a1.75 1.75 0 0 1 .85-1.501M14.25 18H19m-2-2l2 2l-2 2m4.5-5.25v6.5");
}

</style>
