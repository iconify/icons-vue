<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nf3up8bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bowling-ball-pins" /></template>
<style>
.nf3up8bls {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.614 12.397q.051.081.12.147t.152.112t.176.07t.188.024h2.5q.095 0 .188-.024q.092-.024.176-.07t.152-.112q.069-.066.12-.147q2.083-3.332-.177-6.396q.541-.836.541-2.001q0-2.25-2.25-2.25T11.25 4q0 1.165.541 2.001q-2.26 3.064-.177 6.396M18.5 16.75q-.095 0-.188-.024q-.092-.024-.176-.07t-.152-.112t-.12-.147q-2.083-3.332.177-6.396Q17.5 9.165 17.5 8q0-2.25 2.25-2.25T22 8q0 1.165-.541 2.001q2.26 3.064.177 6.396q-.051.081-.12.147t-.152.112q-.084.046-.176.07q-.093.024-.188.024zM1.25 16.5q0-2.175 1.538-3.712Q4.325 11.25 6.5 11.25t3.712 1.538q1.538 1.537 1.538 3.712t-1.538 3.712Q8.675 21.75 6.5 21.75t-3.712-1.538Q1.25 18.675 1.25 16.5");
}

</style>
