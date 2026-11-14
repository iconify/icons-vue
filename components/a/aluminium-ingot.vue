<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9o_vsbdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aluminium-ingot" /></template>
<style>
.m9o_vsbdk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.268 14.197l1.833-5.5A1.75 1.75 0 0 1 6.761 7.5h10.478a1.75 1.75 0 0 1 1.66 1.197l1.833 5.5a1.75 1.75 0 0 1-1.66 2.303H4.928a1.75 1.75 0 0 1-1.66-2.303m.982-2.947h15.5");
}

</style>
