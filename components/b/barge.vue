<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_u79lk2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:barge" /></template>
<style>
.j_u79lk2z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10.5h19l-2 4.5h-15Zm3.75-5h1.5A1.75 1.75 0 0 1 9.5 7.25v1.5a1.75 1.75 0 0 1-1.75 1.75h-1.5A1.75 1.75 0 0 1 4.5 8.75v-1.5A1.75 1.75 0 0 1 6.25 5.5m-3.75 13q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
