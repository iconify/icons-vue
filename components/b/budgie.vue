<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hctg5u8ij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:budgie" /></template>
<style>
.hctg5u8ij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 3c2.5 0 4 2 4 4.5c0 3 1.5 5 3 7l4.5 6l-2 1l-5.25-5c-3.75 0-6.25-3-6.25-6.5c-1.5 0-2.25-1-2-2.5c.25-2.5 2-4.5 4-4.5m.25 3.5h.01M11.5 16v3M3 19h9.25");
}

</style>
