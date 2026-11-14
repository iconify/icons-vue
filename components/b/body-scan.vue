<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbte9kbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:body-scan" /></template>
<style>
.kbte9kbzp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 10h1.75q1.875 0 2.25 1.5l1.75 2.25c.25.75-.25 1.5-1 1.5s-1-.5-1.25-.75l-1-1.5l.5 1.75l.5 4c.25.5-.25 1-.75 1h-1c-.5 0-.75-.5-.75-.75l-.5-3.25c0-.5-1-.5-1 0L11 19c0 .25-.25.75-.75.75h-1c-.5 0-1-.5-.75-1l.5-4L9.5 13l-1 1.5c-.25.25-.5.75-1.25.75s-1.25-.75-1-1.5L8 11.5q.375-1.5 2.25-1.5Zm-1.75-3.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M4 12h16M2.5 2.5V5m0-2.5H5m16.5 0H19m2.5 0V5m-19 16.5V19m0 2.5H5m16.5 0H19m2.5 0V19");
}

</style>
