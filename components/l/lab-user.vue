<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujidgybqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lab-user" /></template>
<style>
.ujidgybqp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5h7M8 2.5V9l-5.5 9.5q-.066.114-.116.236t-.084.249t-.051.257t-.017.263q0 .131.018.262q.017.13.052.257t.085.249q.051.121.117.235q.067.114.147.218q.081.104.175.196t.198.172t.22.145q.114.065.236.114q.122.05.25.083q.127.033.258.049q.13.016.262.015h7.207m2.74-8.704L12 9V2.5m4 13.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-1.75 6c0-1.75 1.75-3 3.75-3s3.75 1.25 3.75 3");
}

</style>
