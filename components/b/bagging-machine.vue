<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_t6d_bit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bagging-machine" /></template>
<style>
.f_t6d_bit {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5h14L13.5 7v2.5h-3V7Zm0 9.75l2.5 2.25c-1.5 2.5-1.5 7 1 7h7c2.5 0 2.5-4.5 1-7l2.5-2.25m-7 0v3.25");
}

</style>
