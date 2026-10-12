<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odq9i6bhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arrow-big-left" /></template>
<style>
.odq9i6bhb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.99 11.01l6.77-6.77q.99-.99.99.41V7.1q0 1.4 1.4 1.4h6.2q1.4 0 1.4 1.4v4.2q0 1.4-1.4 1.4h-6.2q-1.4 0-1.4 1.4v2.45q0 1.4-.99.41l-6.77-6.77q-.99-.99 0-1.98");
}

</style>
