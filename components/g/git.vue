<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gd2i9bctv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:git" /></template>
<style>
.gd2i9bctv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.5 5q0-1.243.878-2.122q.879-.879 2.122-.879t2.122.879T9.5 5t-.878 2.122q-.563.563-1.276.765q.597 1.938 4.896 3.403q5.373 1.832 5.941 4.754Q20.5 16.363 20.5 19q0 3-3 3t-3-3q0-2.534 2.141-2.928q-.629-1.912-4.883-3.362q-3.006-1.025-4.508-2.391v5.768q.771.19 1.372.791q.878.879.878 2.122t-.878 2.122t-2.122.879t-2.122-.879T3.5 19t.878-2.122q.601-.601 1.372-.791V7.913q-.771-.19-1.372-.791Q3.5 6.243 3.5 5");
}

</style>
