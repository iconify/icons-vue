<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hj4dvybzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fruit-basket" /></template>
<style>
.hj4dvybzk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12h18l-1.75 7c-.25 1-1 1.5-2 1.5H6.75c-1 0-1.75-.5-2-1.5Zm1.5-4a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m8 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

</style>
