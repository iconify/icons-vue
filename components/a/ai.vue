<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2dr4uj2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ai" /></template>
<style>
.r2dr4uj2z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 6.5Q9.5 14 17 14q-7.5 0-7.5 7.5Q9.5 14 2 14q7.5 0 7.5-7.5m9-4.25q0 2.25 2.25 2.25q-2.25 0-2.25 2.25q0-2.25-2.25-2.25q2.25 0 2.25-2.25M20 9.5c0 1.25.75 2 2 2c-1.25 0-2 .75-2 2c0-1.25-.75-2-2-2c1.25 0 2-.75 2-2");
}

</style>
