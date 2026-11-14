<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvma8zlxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:foreclosure" /></template>
<style>
.wvma8zlxr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.465 9.137q-1.214 1.011-1.215 2.592v6.646q0 1.398.989 2.386q.988.989 2.386.989H9.75q-1.036 0-1.768-.732T7.25 19.25v-3.5q0-2.092 1.75-2.433V12.5q0-3 3-3t3 3v.817q1.75.341 1.75 2.433v3.5q0 1.036-.732 1.768t-1.768.732h4.125q3.375 0 3.375-3.375v-6.646q-.001-1.581-1.215-2.592L14.16 3.824q-2.16-1.799-4.32 0zM13.5 12.5v.75h-3v-.75q0-1.5 1.5-1.5t1.5 1.5");
}

</style>
