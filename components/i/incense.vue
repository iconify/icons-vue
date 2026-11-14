<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjvr-vdsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:incense" /></template>
<style>
.wjvr-vdsy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 20.5L14.5 10M4 20.5h16m-4-13c1.5-1.5-1-2.75.5-5m3 7.5c1.5-1.5-1-2.75.5-5");
}

</style>
