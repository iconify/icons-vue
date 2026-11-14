<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rj0dagwqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lingerie-department" /></template>
<style>
.rj0dagwqk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 16c0-4.5 2.25-6.5 4.5-6.5s4.5 2 4.5 6.5m0 0c0-4.5 2.25-6.5 4.5-6.5s4.5 2 4.5 6.5M3.75 16h16.5a1.25 1.25 0 0 1 1.25 1.25a1.25 1.25 0 0 1-1.25 1.25H3.75a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 3.75 16M7.5 9.5L6.5 3m10 6.5l1-6.5");
}

</style>
