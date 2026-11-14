<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3pqqzqly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gap" /></template>
<style>
.j3pqqzqly {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 4za2 2 0 0 1 2 2v12a2 2 0 0 1-2 2a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2m15 0za2 2 0 0 1 2 2v12a2 2 0 0 1-2 2a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2M9.25 12h5.5m-3.5-2l-2 2l2 2m1.5-4l2 2l-2 2");
}

</style>
