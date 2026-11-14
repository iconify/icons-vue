<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3g7_tbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kantha-quilt" /></template>
<style>
.s3g7_tbrr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6v-.5A2.5 2.5 0 0 1 5.5 3H6m12 0h.5A2.5 2.5 0 0 1 21 5.5V6m0 12v.5a2.5 2.5 0 0 1-2.5 2.5H18M6 21h-.5A2.5 2.5 0 0 1 3 18.5V18M8.5 3h2.25m2.5 0h2.25m-7 18h2.25m2.5 0h2.25M3 8.5v2.25m0 2.5v2.25m18-7v2.25m0 2.5v2.25M8 6.25h.75A1.75 1.75 0 0 1 10.5 8v.75a1.75 1.75 0 0 1-1.75 1.75H8a1.75 1.75 0 0 1-1.75-1.75V8A1.75 1.75 0 0 1 8 6.25m7.25 0H16A1.75 1.75 0 0 1 17.75 8v.75A1.75 1.75 0 0 1 16 10.5h-.75a1.75 1.75 0 0 1-1.75-1.75V8a1.75 1.75 0 0 1 1.75-1.75M8 13.5h.75a1.75 1.75 0 0 1 1.75 1.75V16a1.75 1.75 0 0 1-1.75 1.75H8A1.75 1.75 0 0 1 6.25 16v-.75A1.75 1.75 0 0 1 8 13.5m7.25 0H16a1.75 1.75 0 0 1 1.75 1.75V16A1.75 1.75 0 0 1 16 17.75h-.75A1.75 1.75 0 0 1 13.5 16v-.75a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
