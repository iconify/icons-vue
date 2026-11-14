<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hy4qysz1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:foot-form" /></template>
<style>
.hy4qysz1z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.5H13v9l5.75 1.5c1.75.5 2.75 1.5 2.75 2.75s-.75 1.75-1.75 1.75H7.5Zm2.75 15v4m-3.75 0H14m-6.5-16H13");
}

</style>
