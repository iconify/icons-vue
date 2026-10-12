<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qz-32ib6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:keyframe" /></template>
<style>
.qz-32ib6x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.85 8.6L5.9 9.65q.35.35 0 .7L4.85 11.4q-.35.35-.7 0L3.1 10.35q-.35-.35 0-.7L4.15 8.6q.35-.35.7 0m7.86-2.14l2.83 2.83q.71.71 0 1.42l-2.83 2.83q-.71.71-1.42 0l-2.83-2.83q-.71-.71 0-1.42l2.83-2.83q.71-.71 1.42 0m7.14 2.14l1.05 1.05q.35.35 0 .7l-1.05 1.05q-.35.35-.7 0l-1.05-1.05q-.35-.35 0-.7l1.05-1.05q.35-.35.7 0M2.75 19h18.5M6 16.75V19m6-2.25V19m6-2.25V19");
}

</style>
