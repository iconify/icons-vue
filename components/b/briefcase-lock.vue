<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqn5bjkgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:briefcase-lock" /></template>
<style>
.rqn5bjkgh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15 5.75h1.5q1.76 0 3.005 1.245T20.75 10v4.01Q19.88 13 18 13q-3.238 0-3.48 2.995Q13 16.863 13 19.25v.5q0 .256.03.5H6q-1.76 0-3.005-1.245T1.75 16v-6q0-1.76 1.245-3.005T6 5.75h1.5V5q0-2.25 2.25-2.25h3Q15 2.75 15 5zm-6 0h4.5V5q0-.75-.75-.75h-3Q9 4.25 9 5zm12.018 11.732q-.35-.349-.768-.532v-.45q0-2.25-2.25-2.25t-2.25 2.25v.377q-1.5.437-1.5 2.373v.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768M18.75 16.5v.25h-1.5v-.25q0-.75.75-.75t.75.75m-3 2.75q0-1 1-1h2.5q.414 0 .707.293t.293.707v.5q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707z");
}

</style>
