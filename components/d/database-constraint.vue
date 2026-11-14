<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="meru30bdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:database-constraint" /></template>
<style>
.meru30bdr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 4.999Q2.751 1.75 9.5 1.75q2.635 0 4.531.79Q16.25 3.464 16.25 5v8.3q-1.089.451-1.5 1.579v-1.787Q13.068 14 9.5 14t-5.25-.908V16.5q0 1.75 5.25 1.75q2.352 0 3.65-.351q-.15.6-.15 1.351v.195q-1.434.305-3.5.305q-6.75 0-6.75-3.25zm12 5.751V7.342q-1.682.908-5.25.908t-5.25-.908v3.408q0 1.75 5.25 1.75t5.25-1.75m6.268 6.732q-.35-.349-.768-.532v-.45q0-2.25-2.25-2.25t-2.25 2.25v.377q-1.5.437-1.5 2.373v.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768M18.75 16.5v.25h-1.5v-.25q0-.75.75-.75t.75.75m-3 2.75q0-1 1-1h2.5q.414 0 .707.293t.293.707v.5q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707z");
}

</style>
