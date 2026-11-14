<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnr4q-3_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:distort-free" /></template>
<style>
.tnr4q-3_s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.292 4.182l4.887-.362m4.966 3.939l1.213 8.009m-3.626 3.521l-6.51-1.085m-4.553-5.011l-.338-4.387M2.5 4.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m13.5-1a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M18.5 20a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-15-2.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
