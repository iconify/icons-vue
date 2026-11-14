<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8sxubbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blowing-snow" /></template>
<style>
.k8sxubbsd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8H14a2.5 2.5 0 1 0-2.5-2.5m-9 6.5H9m-6.5 4h14a2.5 2.5 0 1 1-2.5 2.5m-.5-6.5h.01m6.99 0h.01M8 20.5h.01");
}

</style>
