<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtrxi-7nu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dim-sum-house" /></template>
<style>
.wtrxi-7nu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.241 6.009q.713-.032 1.427-.004q-.281-.255-.668-.255q-.509 0-.759.259m3.195.157q3.72.531 7.44 2.685q.129.075.22.193q.09.119.129.263q.038.144.018.292q-.019.148-.094.277q-.049.085-.119.155t-.155.119t-.181.075q-.095.025-.194.025h-.75v8.25q0 2.25-2.25 2.25h-13q-2.25 0-2.25-2.25v-8.25H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 9.574 1.75 9.5q0-.099.025-.194t.075-.181t.119-.155t.155-.119Q5.831 6.705 9.538 6.17Q9.809 4.25 12 4.25q1.036 0 1.768.732q.516.517.668 1.184m4.814 6.084H4.75v-2h14.5zm0 1.5H4.75v2h14.5zm0 3.5H4.75v1.25q0 .75.75.75h13q.75 0 .75-.75z");
}

</style>
