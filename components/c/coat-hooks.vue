<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg_xe8bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coat-hooks" /></template>
<style>
.bg_xe8bsw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 6.5h15.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 19.75 10H4.25A1.75 1.75 0 0 1 2.5 8.25A1.75 1.75 0 0 1 4.25 6.5M4.5 10v6.5a1.5 1.5 0 0 0 3 0v-1m3-5.5v6.5a1.5 1.5 0 0 0 3 0v-1m3-5.5v6.5a1.5 1.5 0 0 0 3 0v-1");
}

</style>
