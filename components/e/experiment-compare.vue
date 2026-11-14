<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="reve07bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:experiment-compare" /></template>
<style>
.reve07bul {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3zA1.5 1.5 0 0 1 8 4.5v4.32a2 2 0 0 0 .037.357l2.024 9.716A1.75 1.75 0 0 1 8.348 21H4.652a1.75 1.75 0 0 1-1.713-2.107l2.024-9.716A2 2 0 0 0 5 8.82V4.5A1.5 1.5 0 0 1 6.5 3m10.75 0za1.5 1.5 0 0 1 1.5 1.5v4.32a2 2 0 0 0 .037.357l2.024 9.716A1.75 1.75 0 0 1 19.098 21h-3.696a1.75 1.75 0 0 1-1.713-2.107l2.024-9.716a2 2 0 0 0 .037-.357V4.5a1.5 1.5 0 0 1 1.5-1.5M3.75 15h5.5m5.25 0H20");
}

</style>
