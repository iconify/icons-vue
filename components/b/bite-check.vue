<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbzl3_1hu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bite-check" /></template>
<style>
.rbzl3_1hu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.447 15.24L15.5 15c.5-3 2-4.5 2.5-7s0-5-2-5s-3 1-5.5 1S7 3 5 3S2.5 5.5 3 8s2 4 2.5 7l1 4.5c.25 1 1.5 1 1.75 0l1.25-5c.25-1 1.75-1 2 0l.636 2.544M14.75 18l2 2L21 15.75");
}

</style>
