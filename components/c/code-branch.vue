<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyy5iwb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:code-branch" /></template>
<style>
.pyy5iwb3x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.5 5.5q0-1.243.878-2.122q.879-.879 2.122-.879t2.122.879T9.5 5.5t-.878 2.122q-.601.601-1.372.791v5.489q1.525-1.008 4.6-1.637q3.806-.778 4.656-1.865Q14.5 9.953 14.5 7.5q0-3 3-3t3 3q0 2.661-2.361 2.962q-.712 2.194-5.989 3.273q-3.889.795-4.691 1.912q.645.213 1.163.731q.878.879.878 2.122t-.878 2.122t-2.122.879t-2.122-.879T3.5 18.5t.878-2.122q.601-.601 1.372-.791V8.413q-.771-.19-1.372-.791Q3.5 6.743 3.5 5.5");
}

</style>
