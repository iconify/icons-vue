<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rojdhbejk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:consumer-rights" /></template>
<style>
.rojdhbejk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4H5l2.5 11.5h6.031m2.4 0h1.4m.225-.224L19.5 7.5H6m1 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m5.503.101q.009.127.039.25q.03.124.08.241t.119.223t.155.2t.186.171t.212.138q.112.059.233.099q.12.041.246.06M14.75 18l2 2L21 15.75");
}

</style>
