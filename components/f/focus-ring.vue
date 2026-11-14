<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol1psehgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:focus-ring" /></template>
<style>
.ol1psehgj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.65 2.644a9.5 9.5 0 0 1 3.799 1.574m2.333 2.333a9.5 9.5 0 0 1 1.574 3.799m0 3.3a9.5 9.5 0 0 1-1.574 3.799m-2.333 2.333a9.5 9.5 0 0 1-3.799 1.574m-3.3 0a9.5 9.5 0 0 1-3.799-1.574m-2.333-2.333a9.5 9.5 0 0 1-1.574-3.799m0-3.3a9.5 9.5 0 0 1 1.574-3.799m2.333-2.333a9.5 9.5 0 0 1 3.799-1.574");
}

</style>
