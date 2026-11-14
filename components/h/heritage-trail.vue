<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6-csyrwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heritage-trail" /></template>
<style>
.m6-csyrwd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5C5 14 9 10.5 12 10.5s7 3.5 9.5 10m-9.5-10V3m1.652.578l.848.297a.927.927 0 0 1 0 1.75l-.848.297A1.242 1.242 0 0 1 12 4.75a1.242 1.242 0 0 1 1.652-1.172M14 18.5h.01m-4.01-2h.01M13 14h.01");
}

</style>
