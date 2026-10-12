<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vem5nrb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:component" /></template>
<style>
.vem5nrb6i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.71 3.46l1.58 1.58q.71.71 0 1.42l-1.58 1.58q-.71.71-1.42 0L9.71 6.46q-.71-.71 0-1.42l1.58-1.58q.71-.71 1.42 0M6.46 9.71l1.58 1.58q.71.71 0 1.42l-1.58 1.58q-.71.71-1.42 0l-1.58-1.58q-.71-.71 0-1.42l1.58-1.58q.71-.71 1.42 0m12.5 0l1.58 1.58q.71.71 0 1.42l-1.58 1.58q-.71.71-1.42 0l-1.58-1.58q-.71-.71 0-1.42l1.58-1.58q.71-.71 1.42 0m-6.25 6.25l1.58 1.58q.71.71 0 1.42l-1.58 1.58q-.71.71-1.42 0l-1.58-1.58q-.71-.71 0-1.42l1.58-1.58q.71-.71 1.42 0");
}

</style>
