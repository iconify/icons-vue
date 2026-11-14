<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylh6k0byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:boom-pole" /></template>
<style>
.ylh6k0byc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20.078 3.922za2.25 2.25 0 0 1 0 3.182l-2.474 2.474a2.25 2.25 0 0 1-3.182 0a2.25 2.25 0 0 1 0-3.182l2.474-2.474a2.25 2.25 0 0 1 3.182 0M3.5 20.5l11-11M7 17l-2.5-2.5");
}

</style>
