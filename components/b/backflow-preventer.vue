<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hu80o5imn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:backflow-preventer" /></template>
<style>
.hu80o5imn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 8.75a5 5 0 1 0 10 0a5 5 0 1 0-10 0m1-3H2.5m0 6H8m8-6h5.5m0 6H16M12 6.5V11m-6 7.25h12.25m-2.5-2.5l2.5 2.5l-2.5 2.5");
}

</style>
