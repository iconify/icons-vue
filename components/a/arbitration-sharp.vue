<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="se3ub9wrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arbitration-sharp" /></template>
<style>
.se3ub9wrt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.07 15.87l-.2.2l-.71.71l-.71-.71l-3.52-3.52l-.71-.71l.71-.71l.2-.2l.71-.71l.71.71l3.52 3.52l.71.71zM11.3 12.7l5.2-5.2M7 18.75h10v2.5H7zM2.75 13.5h3.5M4 11.25l2.25 2.25L4 15.75m17.25-2.25h-3.5M20 11.25l-2.25 2.25L20 15.75");
}

</style>
