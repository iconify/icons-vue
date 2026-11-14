<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gi_t4uikr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fiber-splice" /></template>
<style>
.gi_t4uikr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 10H4.5a2 2 0 0 0 0 4H8m8-4h3.5a2 2 0 0 1 0 4H16M8 7h8v10H8Zm4 2.5v5");
}

</style>
