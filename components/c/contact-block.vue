<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evnqbtbyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:contact-block" /></template>
<style>
.evnqbtbyh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 8.25q0-1.864 1.318-3.182T9 3.75t3.182 1.318T13.5 8.25t-1.318 3.182T9 12.75t-3.182-1.318T4.5 8.25m10 2.5q0-4 4-4t4 4t-4 4t-4-4m2.768 2.293q.512.207 1.232.207q2.5 0 2.5-2.5q0-.72-.207-1.232zm2.464-4.586Q19.22 8.25 18.5 8.25q-2.5 0-2.5 2.5q0 .72.207 1.232zM3.963 15.985Q1.75 17.573 1.75 20q0 1.75 1.75 1.75h11q1.75 0 1.75-1.75q0-2.427-2.213-4.015Q11.97 14.5 9 14.5t-5.037 1.485");
}

</style>
