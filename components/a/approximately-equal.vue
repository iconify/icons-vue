<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqyg6ebur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:approximately-equal" /></template>
<style>
.uqyg6ebur {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 9.75c1.75-2 3.75-2.5 7.25-1s5.5 1 7.25-1m-14.5 8.5c1.75-2 3.75-2.5 7.25-1s5.5 1 7.25-1");
}

</style>
