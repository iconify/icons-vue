<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c36zljhnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lockout-kit" /></template>
<style>
.c36zljhnf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m1.788 8.763l2-6q.019-.056.046-.108t.062-.099t.076-.089q.042-.041.089-.075q.048-.035.1-.061q.053-.027.109-.045q.055-.018.113-.027T4.5 2.25H16q.059 0 .117.009t.113.027q.056.018.109.045q.052.026.1.061q.047.034.089.075t.076.089t.062.099t.046.108l1.999 5.999l.001.001q.036.108.038.223v4.059Q18.398 13 18 13q-3.238 0-3.48 2.995Q13 16.863 13 19.25H4q-2.25 0-2.25-2.25V9q0-.122.038-.237M15.459 3.75H5.041l-1.5 4.5h13.418zm5.559 13.732q-.35-.349-.768-.532v-.45q0-2.25-2.25-2.25t-2.25 2.25v.377q-1.5.437-1.5 2.373v.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768M18.75 16.5v.25h-1.5v-.25q0-.75.75-.75t.75.75m-3 3.25v-.5q0-1 1-1h2.5q.414 0 .707.293t.293.707v.5q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707");
}

</style>
