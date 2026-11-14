<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jehmku8jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gym-membership" /></template>
<style>
.jehmku8jc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 6za2 2 0 0 1 2 2v8a2 2 0 0 1-2 2a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2m14 0za2 2 0 0 1 2 2v8a2 2 0 0 1-2 2a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2M7 12h10");
}

</style>
