<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6_8hebry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bread-basket" /></template>
<style>
.s6_8hebry {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11.5h18l-1.75 7.25c-.25 1-1 1.75-2 1.75H6.75c-1 0-1.75-.75-2-1.75Zm1 4h16m-15.5-4c0-4 2-6 4.5-6s4.5 2 4.5 6m0 0c0-3 1.75-4.5 3.5-4.5s3 1.5 3 4.5");
}

</style>
