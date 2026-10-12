<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qh5jybbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:conference-call" /></template>
<style>
.qh5jybbsu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 14h10q1.75 0 2.45 1.6l1.1 2.55q.7 1.6-1.05 1.6h-15q-1.75 0-1.05-1.6l1.1-2.55Q5.25 14 7 14m1.5 0a3.5 3 0 0 1 7 0Zm-.75 3h8.5m-8-8.25a5.25 5.25 0 0 1 7.5 0m-10-2.5a8.75 8.75 0 0 1 12.5 0");
}

</style>
