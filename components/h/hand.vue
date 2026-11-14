<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5c5vv7af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hand" /></template>
<style>
.f5c5vv7af {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 21.5V19l-3.25-4.75a1.5 1.5 0 0 1 2.5-1.75L8.5 14V5.5a1.5 1.5 0 0 1 3 0V11V4a1.5 1.5 0 0 1 3 0v7v-5.5a1.5 1.5 0 0 1 3 0v6V8a1.5 1.5 0 0 1 3 0v7c0 3-2 4.5-3.5 4.5v2");
}

</style>
