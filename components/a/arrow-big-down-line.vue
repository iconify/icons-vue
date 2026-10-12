<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agyw-e8jb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrow-big-down-line" /></template>
<style>
.agyw-e8jb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.01 20.01l-6.77-6.77q-.99-.99.41-.99H7.1q1.4 0 1.4-1.4v-6.2q0-1.4 1.4-1.4h4.2q1.4 0 1.4 1.4v6.2q0 1.4 1.4 1.4h2.45q1.4 0 .41.99l-6.77 6.77q-.99.99-1.98 0");
}

</style>
