<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5qyv_b0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:emergency-bottled-water" /></template>
<style>
.k5qyv_b0d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 20.5V10L6 8V4.5h2V8l1.5 2L11 8V4.5h2V8l1.5 2L16 8V4.5h2V8l1.5 2v10.5m-17 0h19M9.5 10v10.5m5-10.5v10.5");
}

</style>
