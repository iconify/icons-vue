<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccc0dbuxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:heart-box-chocolates" /></template>
<style>
.ccc0dbuxv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.688 2.75h14.625q2.937.001 2.937 2.938v.125q-.001 2.098-1.5 2.697V19.5q0 2-2 2H5.25q-2 0-2-2V8.51q-1.499-.599-1.5-2.697v-.125q0-1.217.861-2.077q.86-.861 2.077-.861m.062 6V19.5q0 .5.5.5h13.5q.5 0 .5-.5V8.75zm6.72 9.28l-3-3q-.016-.015-.031-.032q-1.8-2.026.116-3.943q1.681-1.68 3.445-.503q1.764-1.177 3.445.503q1.916 1.917.116 3.943q-.015.017-.031.032l-3 3q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094");
}

</style>
