<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzggkoxtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bearing" /></template>
<style>
.qzggkoxtb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.891 7.237q.71-1.334 1.861-2.485Q7.754 1.75 12 1.75Q8.75 1.75 8.75 5T12 8.25T15.25 5T12 1.75q4.246 0 7.248 3.002q1.151 1.151 1.861 2.485q-.811-.737-2.359-.737q-3.25 0-3.25 3.25T18.75 13T22 9.75l-.001-.1q.251 1.123.251 2.35q0 4.246-3.002 7.248q-.195.195-.395.377q.397-.739.397-1.875q0-3.25-3.25-3.25t-3.25 3.25T16 21q.667 0 1.197-.137Q14.886 22.25 12 22.25t-5.197-1.387Q7.333 21 8 21q1.346 0 2.298-.952t.952-2.298t-.952-2.298T8 14.5q-3.25 0-3.25 3.25q0 1.136.397 1.875q-.2-.182-.395-.377Q1.75 16.246 1.75 12q0-1.227.251-2.35L2 9.75Q2 13 5.25 13T8.5 9.75q0-1.346-.952-2.298T5.25 6.5q-1.548 0-2.359.737");
}

</style>
