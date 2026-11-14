<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk4s_6bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:film-canister" /></template>
<style>
.uk4s_6bop {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 6.5h8v13A1.5 1.5 0 0 1 10 21H5a1.5 1.5 0 0 1-1.5-1.5Zm.75-3h6.5a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-6.5A1.5 1.5 0 0 1 2.75 5a1.5 1.5 0 0 1 1.5-1.5m7.25 7h10V16h-10m3.5-2.75h.01m3.49 0h.01");
}

</style>
