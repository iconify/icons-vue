<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_rk1t--x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gadget-console-cover" /></template>
<style>
.p_rk1t--x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 7h8.5a5.25 5.25 0 0 1 5.25 5.25a5.25 5.25 0 0 1-5.25 5.25h-8.5a5.25 5.25 0 0 1-5.25-5.25A5.25 5.25 0 0 1 7.75 7m-.25 3.25v4m-2-2h4m6-1.25h.01M18 13.5h.01");
}

</style>
