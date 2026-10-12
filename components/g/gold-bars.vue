<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk8mbdblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gold-bars" /></template>
<style>
.lk8mbdblc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 19.53l1-3.81q.25-.97 1.25-.97h3q1 0 1.25.97l1 3.81q.25.97-.75.97h-6q-1 0-.75-.97m10.5 0l1-3.81q.25-.97 1.25-.97h3q1 0 1.25.97l1 3.81q.25.97-.75.97h-6q-1 0-.75-.97M8 11.28l1-3.81q.25-.97 1.25-.97h3.5q1 0 1.25.97l1 3.81q.25.97-.75.97h-6.5q-1 0-.75-.97");
}

</style>
