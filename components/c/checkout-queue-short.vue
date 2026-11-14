<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmalx9b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:checkout-queue-short" /></template>
<style>
.vmalx9b4l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m12.125 3.5h1.75A2.625 2.625 0 0 1 21 13.125v5.25A2.625 2.625 0 0 1 18.375 21h-1.75A2.625 2.625 0 0 1 14 18.375v-5.25a2.625 2.625 0 0 1 2.625-2.625M2.5 21v-4a4.5 4.5 0 0 1 9 0v4m5-7h2M16.75 4h1.5A1.75 1.75 0 0 1 20 5.75a1.75 1.75 0 0 1-1.75 1.75h-1.5A1.75 1.75 0 0 1 15 5.75A1.75 1.75 0 0 1 16.75 4");
}

</style>
