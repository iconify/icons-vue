<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b42ye73dd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dog-face" /></template>
<style>
.b42ye73dd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 4.5h7c3 0 5.25 1 5.5 3.5l.5 5c.25 2.5-2.5 3-3 1l-1.75-5.25V15c0 3.75-2.25 6-4.75 6s-4.75-2.25-4.75-6V8.75L5.5 14c-.5 2-3.25 1.5-3-1L3 8c.25-2.5 2.5-3.5 5.5-3.5M10 11h.01M14 11h.01M12 15.25h.01");
}

</style>
