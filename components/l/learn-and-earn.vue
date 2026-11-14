<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnz493b1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:learn-and-earn" /></template>
<style>
.nnz493b1k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.641 2.302l5.487 2.592a1.5 1.5 0 0 1 0 2.712l-5.487 2.592a1.5 1.5 0 0 1-1.282 0L5.872 7.606a1.5 1.5 0 0 1 0-2.712l5.487-2.592a1.5 1.5 0 0 1 1.282 0M21 6.25v4.25m-13 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0m4 0h.01");
}

</style>
