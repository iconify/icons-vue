<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7p8k2bbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:boxers-sparring" /></template>
<style>
.l7p8k2bbw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 9.75zA3.25 3.25 0 0 1 12 13v3.5a3.25 3.25 0 0 1-3.25 3.25A3.25 3.25 0 0 1 5.5 16.5V13a3.25 3.25 0 0 1 3.25-3.25m-4.75 2za1.5 1.5 0 0 1 1.5 1.5v3a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5v-3a1.5 1.5 0 0 1 1.5-1.5m11.25-2zA3.25 3.25 0 0 1 18.5 13v3.5a3.25 3.25 0 0 1-3.25 3.25A3.25 3.25 0 0 1 12 16.5V13a3.25 3.25 0 0 1 3.25-3.25m4.75 2za1.5 1.5 0 0 1 1.5 1.5v3a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5v-3a1.5 1.5 0 0 1 1.5-1.5M12 4v3M8.5 4.5L9.75 7m5.75-2.5L14.25 7");
}

</style>
