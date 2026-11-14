<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5lo2rzft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:code-merge" /></template>
<style>
.i5lo2rzft {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.5 5.5q0-1.243.878-2.122q.879-.879 2.122-.879t2.122.879T9.5 5.5t-.878 2.122q-.591.591-1.347.785q.218 2.838 2.349 4.969q2.118 2.118 4.934 2.346q.36-2.222 2.942-2.222q3 0 3 3t-3 3q-2.612 0-2.95-2.274q-3.431-.233-5.987-2.789q-.759-.76-1.313-1.596v2.746q.771.19 1.372.791q.878.879.878 2.122t-.878 2.122t-2.122.879t-2.122-.879T3.5 18.5t.878-2.122q.601-.601 1.372-.791V8.413q-.771-.19-1.372-.791Q3.5 6.743 3.5 5.5");
}

</style>
