<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kralml_9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gantt-locked" /></template>
<style>
.kralml_9m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 2.75h5q1.036 0 1.768.732t.732 1.768q0 2.5-2.5 2.5h-5q-2.5 0-2.5-2.5t2.5-2.5m11 6.75h-6.5q-2.5 0-2.5 2.5q0 1.036.732 1.768t1.768.732h5.667Q15.709 13 18 13h.05q.2-.458.2-1q0-2.5-2.5-2.5m5.268 7.982q-.35-.349-.768-.532v-.45q0-2.25-2.25-2.25t-2.25 2.25v.377q-1.5.437-1.5 2.373v.5q0 1.036.732 1.768t1.768.732h2.5q1.036 0 1.768-.732t.732-1.768v-.5q0-1.036-.732-1.768M18.75 16.5v.25h-1.5v-.25q0-.75.75-.75t.75.75m-16.5 2.25q0-2.5 2.5-2.5h5.5q1.036 0 1.768.732t.732 1.768t-.732 1.768t-1.768.732h-5.5q-2.5 0-2.5-2.5m13.5.5q0-1 1-1h2.5q.414 0 .707.293t.293.707v.5q0 .414-.293.707t-.707.293h-2.5q-.414 0-.707-.293t-.293-.707z");
}

</style>
