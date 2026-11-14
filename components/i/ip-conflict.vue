<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpa3o_b2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ip-conflict" /></template>
<style>
.dpa3o_b2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 3h4.5a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 8.75 8.5h-4.5A1.75 1.75 0 0 1 2.5 6.75v-2A1.75 1.75 0 0 1 4.25 3m11 0h4.5a1.75 1.75 0 0 1 1.75 1.75v2a1.75 1.75 0 0 1-1.75 1.75h-4.5a1.75 1.75 0 0 1-1.75-1.75v-2A1.75 1.75 0 0 1 15.25 3M6.5 8.5V11q5.5 3.5 11 0V8.5m.5 6V18m0 3h.01");
}

</style>
