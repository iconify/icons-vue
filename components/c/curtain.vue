<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmgx64b1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:curtain" /></template>
<style>
.kmgx64b1g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.25h18.5m-17 2.5h6.25c0 6.25-1.5 11-4.75 15.5h-1.5Zm15.5 0H13.5c0 6.25 1.5 11 4.75 15.5h1.5Z");
}

</style>
