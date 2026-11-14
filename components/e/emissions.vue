<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-3ffbbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:emissions" /></template>
<style>
.a-3ffbbmp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20v-7H4V9.5h3V13h5V9.5h3V13l3-2.5V13l3.5-2.5V20Zm1-14.75a2 1.5 0 1 0 4 0a2 1.5 0 1 0-4 0m8 0a2 1.5 0 1 0 4 0a2 1.5 0 1 0-4 0");
}

</style>
