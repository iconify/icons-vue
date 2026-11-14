<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bojd2zb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cheque-image-clearing" /></template>
<style>
.bojd2zb1q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 5.5H4.5a2 2 0 0 0-2 2v9a2 2 0 0 0 2 2h4.25m-3.5-9h1m-1 5h1m5.25-9H13V7h-1.5Zm0 5.75H13v1.5h-1.5Zm0 5.75H13v1.5h-1.5Zm4.25-8.75h1.5v1.5h-1.5Zm0 5.75h1.5v1.5h-1.5ZM20 11.25h1.5v1.5H20Z");
}

</style>
