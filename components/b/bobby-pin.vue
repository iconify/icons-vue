<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l97qxpbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bobby-pin" /></template>
<style>
.l97qxpbxz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 21.5V6a3.5 3.5 0 0 1 7 0m0 0v2.5l1.75 2l-1.75 2l1.75 2l-1.75 2v5");
}

</style>
