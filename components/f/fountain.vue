<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xzufxybwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fountain" /></template>
<style>
.xzufxybwu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 16h16.5v2.75a2.5 2.5 0 0 1-2.5 2.5H6.25a2.5 2.5 0 0 1-2.5-2.5ZM8.5 9.75h7a3.5 3.5 0 0 1-2.75 3.4V16h-1.5v-3.1A3.5 3.5 0 0 1 8.5 9.75m3.5 0v-5m0 0c-3.5-2.5-8.25-1-8.25 5v3m8.25-8c3.5-2.5 8.25-1 8.25 5v3");
}

</style>
