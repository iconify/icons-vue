<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lavif2bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lighthouse" /></template>
<style>
.lavif2bxn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.33 20.5l1.09-10.25q.08-.75.83-.75h3.5q.75 0 .83.75l1.09 10.25q.08.75-.67.75H9q-.75 0-.67-.75m-.83-11h9M9.75 6.15V5.6q0-.6.42-1.02l1.41-1.41q.42-.42.84 0l1.41 1.41q.42.42.42 1.02v.55q0 .6-.6.6h-3.3q-.6 0-.6-.6m-.65 7.1h5.8M8.7 17h6.6M2.75 4.5L6.5 5.75M21.25 4.5L17.5 5.75");
}

</style>
