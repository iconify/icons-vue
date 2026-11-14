<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_klp1bea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:architect" /></template>
<style>
.z_klp1bea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.772 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.115 0 2.16.155 3.097.442M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0m7.621 14.5H20a1.5 1.5 0 0 0 1.5-1.5v-5.879a1.5 1.5 0 0 0-2.561-1.06l-5.878 5.878a1.5 1.5 0 0 0 1.06 2.561");
}

</style>
