<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7khu_bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:airbrush" /></template>
<style>
.s7khu_bpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8H13l5 2l-5 2H4.5a2 2 0 0 1 0-4m4 4q.5 3-1 5.5M20.5 7h.01m.49 3h.01m-.51 3h.01");
}

</style>
