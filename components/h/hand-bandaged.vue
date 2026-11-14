<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onh05ivda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hand-bandaged" /></template>
<style>
.onh05ivda {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 21.5v-3L4.25 14a1.5 1.5 0 0 1 2.25-2l.5.5V8a1.5 1.5 0 0 1 3 0V4.5a1.5 1.5 0 0 1 3 0v1a1.5 1.5 0 0 1 3 0V8a1.5 1.5 0 0 1 3 0v8.5c0 1.75-1 2.5-2.5 3.25v1.75M7 8.5L19 13M7 12l12 4.5");
}

</style>
