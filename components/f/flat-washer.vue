<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0zdmwz3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:flat-washer" /></template>
<style>
.c0zdmwz3a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 10.5q-.001-2.7 2.994-4.53Q8.06 4.248 12 4.248t6.756 1.722q2.996 1.831 2.994 4.53V13q-.002 2.698-2.996 4.528q-2.816 1.72-6.754 1.72t-6.754-1.72Q2.252 15.698 2.25 13zm5.5 0q0-2.75 4.25-2.75q1.649 0 2.847.685q1.403.801 1.403 2.065q0 2.75-4.25 2.75T7.75 10.5m-3.789 3.585q.482 1.194 2.067 2.163q2.456 1.5 5.972 1.5t5.972-1.5q1.585-.969 2.067-2.163q-.552.499-1.283.945Q15.94 16.752 12 16.752T5.244 15.03q-.731-.446-1.283-.945");
}

</style>
