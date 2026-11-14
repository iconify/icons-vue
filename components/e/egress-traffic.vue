<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdz85vb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:egress-traffic" /></template>
<style>
.cdz85vb5j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 4h4a3.5 3.5 0 0 1 3.5 3.5v9A3.5 3.5 0 0 1 10 20H6a3.5 3.5 0 0 1-3.5-3.5v-9A3.5 3.5 0 0 1 6 4m10.25 8h5.25m-3-3l3 3l-3 3m-16-3h11M6 8h.01M6 16h.01");
}

</style>
