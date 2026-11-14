<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol7qm3bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:firecracker" /></template>
<style>
.ol7qm3bfc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.242 14.515l4.773-4.773a2.625 2.625 0 0 1 3.712 0l.531.531a2.625 2.625 0 0 1 0 3.712l-4.773 4.773a2.625 2.625 0 0 1-3.712 0l-.531-.531a2.625 2.625 0 0 1 0-3.712M14 10q.75-1.75 2.25-2.25m1.75-3V3m1.25 3H21m-2-1l1.25-1.25M17 5l-1.25-1.25");
}

</style>
