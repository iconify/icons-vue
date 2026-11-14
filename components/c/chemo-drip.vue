<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8t9p-ves"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chemo-drip" /></template>
<style>
.a8t9p-ves {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3.5h10V10c0 2-2 3.5-5 4.5c-3-1-5-2.5-5-4.5Zm5 11V17m0 0za2 2 0 0 1 2 2v.5a2 2 0 0 1-2 2a2 2 0 0 1-2-2V19a2 2 0 0 1 2-2m0-8.5h.01");
}

</style>
