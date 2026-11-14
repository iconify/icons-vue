<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxvxcgbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:catering-tray" /></template>
<style>
.gxvxcgbgs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.581 12h14.838a1.5 1.5 0 0 1 1.423 1.974l-1.5 4.5a1.5 1.5 0 0 1-1.423 1.026H6.081a1.5 1.5 0 0 1-1.423-1.026l-1.5-4.5A1.5 1.5 0 0 1 4.581 12M4 12l1-4.5l2.5 1.25L9.75 6l2.5 2l2.25-2.75l2.5 2.5l2.25-1L20 12M7 15.75h10");
}

</style>
