<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_8fcobcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:end-of-season" /></template>
<style>
.q_8fcobcf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.966 14.361C10.347 16.644 6.882 18 3 18C3 10 7.5 3 18 3c0 3.874-1.35 7.332-3.624 9.949M3 18l9-9m2.75 12.25l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

</style>
