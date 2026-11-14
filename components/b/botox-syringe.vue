<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlb3kd7tt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:botox-syringe" /></template>
<style>
.nlb3kd7tt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m18.01 5.99l-2.121 2.121m-1.768-1.768l3.536 3.536m-1.768-1.768za1.75 1.75 0 0 1 0 2.475l-3.182 3.182a1.75 1.75 0 0 1-2.475 0a1.75 1.75 0 0 1 0-2.475l3.182-3.182a1.75 1.75 0 0 1 2.475 0m-5.657 5.657l-2.121 2.121m-1.414-1.414l2.828 2.828M17.5 14.5c.25 2 1 2.75 3 3c-2 .25-2.75 1-3 3c-.25-2-1-2.75-3-3c2-.25 2.75-1 3-3");
}

</style>
