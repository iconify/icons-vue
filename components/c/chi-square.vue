<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4vxu7btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chi-square" /></template>
<style>
.y4vxu7btz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 9l9 11m0-11L4 20M16.5 4.5a1.75 1.75 0 0 1 3.5.25c0 1.5-3.5 2.25-3.5 3.75h4");
}

</style>
