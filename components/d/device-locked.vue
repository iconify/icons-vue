<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlule400w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:device-locked" /></template>
<style>
.dlule400w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.25 2.25h-5.5q-2.485 0-4.243 1.757Q1.75 5.765 1.75 8.25v5.5q0 2.485 1.757 4.243Q5.265 19.75 7.75 19.75H13v-.5q0-2.387 1.52-3.255Q14.762 13 18 13q.694 0 1.25.138V8.25q0-2.485-1.757-4.243Q15.735 2.25 13.25 2.25M6 10q0-3.5 3.5-3.5T13 10t-3.5 3.5T6 10m15.018 7.482q-.35-.349-.768-.532v-.45q0-2.25-2.25-2.25t-2.25 2.25v.377q-1.5.437-1.5 2.373v.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768M18.75 16.5v.25h-1.5v-.25q0-.75.75-.75t.75.75m-3 2.75q0-1 1-1h2.5q.414 0 .707.293t.293.707v.5q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707z");
}

</style>
