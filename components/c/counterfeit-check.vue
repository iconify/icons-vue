<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxuchg8fa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:counterfeit-check" /></template>
<style>
.qxuchg8fa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.571 4.429za3.5 3.5 0 0 1 0 4.95l-9.192 9.192a3.5 3.5 0 0 1-4.95 0a3.5 3.5 0 0 1 0-4.95l9.192-9.192a3.5 3.5 0 0 1 4.95 0M9.025 9.025l4.95 4.95M14.75 18l2 2L21 15.75");
}

</style>
