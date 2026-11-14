<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_ffzvwos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bag-size-large" /></template>
<style>
.l_ffzvwos {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7h15l1 8h-17Zm4 0V5.5a3.5 3.5 0 0 1 7 0V7M3 19.75h18m-16-2l-2 2l2 2m14-4l2 2l-2 2");
}

</style>
