<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yhn_dvbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:airplane-mode-off" /></template>
<style>
.yhn_dvbbq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 6.55V4.5c0-1 .5-2 1.5-2s1.5 1 1.5 2v5L21 14v2l-1.572-.472M13.5 17.461V18l2.016 1.411m.484.549v1.54l-4-1.25l-4 1.25v-1.75L10.5 18v-3.576m-.504-.523L3 16v-2l4.37-2.622M3.5 3.5l17 17");
}

</style>
