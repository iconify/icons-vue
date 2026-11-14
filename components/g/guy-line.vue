<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5cwpb0ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:guy-line" /></template>
<style>
.d5cwpb0ad {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.408 18.404l4.216-9.728a1.5 1.5 0 0 1 2.752 0l4.216 9.728a1.5 1.5 0 0 1-1.377 2.096h-8.43a1.5 1.5 0 0 1-1.377-2.096M9 5.5v-3m0 0L21 16m0 0v4.5M9 14v6.5");
}

</style>
