<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvqwkbc8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arctic-fox" /></template>
<style>
.kvqwkbc8x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 21l-5-4l-3.75-2.5l2.25-3l-.75-8l4.75 4h5l4.75-4l-.75 8l2.25 3L17 17Zm-2.5-9h.01m4.99 0h.01M12 17h.01");
}

</style>
