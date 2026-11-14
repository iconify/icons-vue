<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lof2_t17p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:camera-timer" /></template>
<style>
.lof2_t17p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 8.5q0-1.139.805-1.945Q3.861 5.75 5 5.75h2.075l1.282-2.136q.05-.083.119-.151q.07-.068.154-.116q.085-.048.179-.072q.094-.025.191-.025h6q.097 0 .191.025q.094.024.179.072t.154.116t.119.151l1.282 2.136H19q2.75 0 2.75 2.75V18q0 2.75-2.75 2.75H5q-2.75 0-2.75-2.75zm6.568 1.318Q7.5 11.136 7.5 13t1.318 3.182T12 17.5t3.182-1.318T16.5 13t-1.318-3.182T12 8.5T8.818 9.818");
}

</style>
