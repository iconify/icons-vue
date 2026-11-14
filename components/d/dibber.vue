<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqb-h43kl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dibber" /></template>
<style>
.vqb-h43kl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 14.5L10 10V4.5a2 2 0 0 1 2-2a2 2 0 0 1 2 2V10Zm-9.5 6c1.5-3 4.5-4 7.5-4l2 2l2-2c3 0 6 1 7.5 4ZM10 10h4");
}

</style>
