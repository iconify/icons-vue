<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_n1qnbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:glucose-test-strip" /></template>
<style>
.h_n1qnbgs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.227 17.237l6.01-6.01a1.75 1.75 0 0 1 2.475 0l1.061 1.061a1.75 1.75 0 0 1 0 2.475l-6.01 6.01a1.75 1.75 0 0 1-2.475 0l-1.061-1.061a1.75 1.75 0 0 1 0-2.475M17.5 2S21 5.5 21 7.5a3.5 3.5 0 0 1-7 0c0-2 3.5-5.5 3.5-5.5M8.354 12.111l3.535 3.535");
}

</style>
