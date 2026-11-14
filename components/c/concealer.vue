<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0lp8js8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:concealer" /></template>
<style>
.s0lp8js8v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 10h7.5v10.5h-7.5Zm2.25 0V5a1.5 1.5 0 0 1 3 0v5m5 10.5V11a3.5 3.5 0 0 1 7 0v9.5Z");
}

</style>
