<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xepu8kbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:archaeology-trowel" /></template>
<style>
.xepu8kbke {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.718 5.282za1.5 1.5 0 0 1 0 2.122L16.95 9.172a1.5 1.5 0 0 1-2.122 0a1.5 1.5 0 0 1 0-2.122l1.768-1.768a1.5 1.5 0 0 1 2.122 0m-3.89 3.89l-1.767 1.767m-1.477-1.476l2.953 2.953a1.75 1.75 0 0 1-.592 2.864l-4.896 1.943a1.75 1.75 0 0 1-2.272-2.272l1.943-4.896a1.75 1.75 0 0 1 2.864-.592");
}

</style>
