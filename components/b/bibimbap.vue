<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sb0m0cjsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bibimbap" /></template>
<style>
.sb0m0cjsu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11h19c0 5.5-4.5 8.5-9.5 8.5s-9.5-3-9.5-8.5m2 0c.5-2.75 2-4.75 4-5m7 0c2 .25 3.5 2.25 4 5m-11-5a3.5 2 0 1 0 7 0a3.5 2 0 1 0-7 0M12 6h.01");
}

</style>
