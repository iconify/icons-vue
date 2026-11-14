<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4914gbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chef-uniform" /></template>
<style>
.k4914gbqg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 4.5L4.5 6l-2 7.5l2.5.75L7 9.5v12h10v-12l2 4.75l2.5-.75l-2-7.5l-4-1.5Zm.75 0v-2h5.5v2M10 10h.01M14 10h.01M10 15h.01M14 15h.01");
}

</style>
