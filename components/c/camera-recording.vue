<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thbcvk34m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camera-recording" /></template>
<style>
.thbcvk34m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 5.25h4.25q2.123 0 3.624 1.501q1.09 1.09 1.389 2.509l2.728-1.592q1.125-.656 2.255-.007q1.129.648 1.129 1.951v4.776q0 1.303-1.129 1.951t-2.255-.007l-2.728-1.592q-.299 1.419-1.389 2.509q-1.501 1.501-3.624 1.501h-4.25q-2.123 0-3.624-1.501T1.75 13.625v-3.25q0-2.123 1.501-3.624T6.875 5.25m-2.125 5q0 2.25 2.25 2.25t2.25-2.25T7 8t-2.25 2.25");
}

</style>
