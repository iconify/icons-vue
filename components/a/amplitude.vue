<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="he8yxo__j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:amplitude" /></template>
<style>
.he8yxo__j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 12c1.5-9.5 4.5-9.5 6 0s4.5 9.5 6 0M4.5 5v7M2.75 6.75L4.5 5l1.75 1.75m-3.5 3.5L4.5 12l1.75-1.75");
}

</style>
