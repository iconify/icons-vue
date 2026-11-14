<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3deybnhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:jump-rope" /></template>
<style>
.w3deybnhf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.25 4q0-2.25-2.25-2.25T2.75 4v2.5q0 1.883 1.576 2.19q.348 3.704 2.278 6.094Q8.798 17.5 12 17.5t5.396-2.716q1.93-2.39 2.278-6.094q1.576-.307 1.576-2.19V4q0-2.25-2.25-2.25T16.75 4v2.5q0 1.787 1.42 2.155q-.322 3.182-1.941 5.186Q14.485 16 12 16t-4.229-2.159Q6.152 11.837 5.83 8.655Q7.25 8.287 7.25 6.5z");
}

</style>
