<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unuy2o_xo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crucible" /></template>
<style>
.unuy2o_xo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 9.75h8.5q1.5 0 1.21 1.47l-1.67 8.56q-.29 1.47-1.79 1.47h-4q-1.5 0-1.79-1.47l-1.67-8.56q-.29-1.47 1.21-1.47m-2.25-3h13a6.5 3.5 0 0 0-13 0");
}

</style>
