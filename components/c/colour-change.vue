<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbccejblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:colour-change" /></template>
<style>
.tbccejblx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 3h7M8.5 3v6l-5 9q-.066.114-.116.236t-.084.249t-.051.257t-.017.263q0 .131.018.262q.017.13.052.257t.085.249q.051.121.117.235q.067.114.147.218q.081.104.175.196t.198.172q.105.08.22.145q.114.065.236.114q.122.05.25.083q.127.033.258.049q.13.016.262.015h7.289m2.449-7.522L12.5 9V3M6 13.5h8.9m.1 2.75h6m-1.75-1.75L21 16.25m0 3.5h-6m1.75 1.75L15 19.75");
}

</style>
