<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-7g_acuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lampshade" /></template>
<style>
.w-7g_acuz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.197 3h7.606a1.75 1.75 0 0 1 1.631 1.116l2.139 5.5A1.75 1.75 0 0 1 17.942 12H6.058a1.75 1.75 0 0 1-1.631-2.384l2.139-5.5A1.75 1.75 0 0 1 8.197 3M12 12v9m-4.5 0h9");
}

</style>
