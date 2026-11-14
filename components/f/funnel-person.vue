<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k97g32ffl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:funnel-person" /></template>
<style>
.k97g32ffl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.305 3.5h9.39a1.75 1.75 0 0 1 1.329 2.889l-3.103 3.619a1.75 1.75 0 0 0-.421 1.139v2.362a1.75 1.75 0 0 1-.85 1.501L11 16a1.651 1.651 0 0 1-2.5-1.415v-3.438a1.75 1.75 0 0 0-.421-1.139L4.976 6.389A1.75 1.75 0 0 1 6.305 3.5M14.5 21.25c0-1.5 1.5-2.5 3.5-2.5s3.5 1 3.5 2.5c0 .25-.25.5-.5.5h-6c-.25 0-.5-.25-.5-.5m1.75-6a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
