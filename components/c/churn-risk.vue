<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu_l3rkbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:churn-risk" /></template>
<style>
.qu_l3rkbb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.072 21H4.5c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.195 0 2.312.178 3.299.506M7 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0ZM18 14l4 7.5h-8Zm0 3.25v1M18 20h.01");
}

</style>
