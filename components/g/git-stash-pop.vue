<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gy517v8bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:git-stash-pop" /></template>
<style>
.gy517v8bd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 12v7.5a2 2 0 0 0 2 2h11a2 2 0 0 0 2-2V12Zm-.492-3.318l4.096-2.868a1.5 1.5 0 0 1 2.089.369a1.5 1.5 0 0 1-.369 2.089L5.729 11.14a1.5 1.5 0 0 1-2.089-.369a1.5 1.5 0 0 1 .368-2.089M17 4v5.25M14.5 6.5L17 4l2.5 2.5");
}

</style>
