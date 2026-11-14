<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjp9yrwup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:caret-up-down" /></template>
<style>
.mjp9yrwup {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.115 5.739L14.25 7a1.498 1.498 0 0 1-1.113 2.5h-2.274A1.498 1.498 0 0 1 9.75 7l1.135-1.261a1.5 1.5 0 0 1 2.23 0m0 12.522L14.25 17a1.498 1.498 0 0 0-1.113-2.5h-2.274A1.498 1.498 0 0 0 9.75 17l1.135 1.261a1.5 1.5 0 0 0 2.23 0");
}

</style>
