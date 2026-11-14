<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ry7do_wsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gaming-table-round" /></template>
<style>
.ry7do_wsf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7a8 2.5 0 1 0 16 0a8 2.5 0 1 0-16 0m8 2.5v11m-3 0h4.8m5.955-6.631l1.931.518a1.75 1.75 0 0 1 1.238 2.143l-1.035 3.864a1.75 1.75 0 0 1-2.144 1.237l-1.931-.518a1.75 1.75 0 0 1-1.238-2.143l1.035-3.864a1.75 1.75 0 0 1 2.144-1.237");
}

</style>
