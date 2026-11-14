<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9iomlbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leg-extension" /></template>
<style>
.d9iomlbks {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3v11.5h9m-5 0v7m-3.5 0h7m1.5-7l3.5-2.75M15.25 10a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
