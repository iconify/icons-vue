<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kosd9kb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:first-aid-bag" /></template>
<style>
.kosd9kb_r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.238 8h9.524a2.625 2.625 0 0 1 2.592 2.21l1.16 7.25a2.625 2.625 0 0 1-2.592 3.04H6.078a2.625 2.625 0 0 1-2.592-3.04l1.16-7.25A2.625 2.625 0 0 1 7.238 8M8.5 8a3.5 3.5 0 0 1 7 0M12 11.5V17m-2.75-2.75h5.5");
}

</style>
