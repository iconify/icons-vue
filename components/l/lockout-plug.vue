<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcvt1kb6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lockout-plug" /></template>
<style>
.bcvt1kb6o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 6h2a3.5 3.5 0 0 1 3.5 3.5v.5A3.5 3.5 0 0 1 9 13.5H7A3.5 3.5 0 0 1 3.5 10v-.5A3.5 3.5 0 0 1 7 6M6 2.5V6m4-3.5V6m-2 7.5V21m8.75-3.5h2.5A1.75 1.75 0 0 1 21 19.25v.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.75v-.5a1.75 1.75 0 0 1 1.75-1.75m-.25 0v-1a1.5 1.5 0 0 1 3 0v1");
}

</style>
