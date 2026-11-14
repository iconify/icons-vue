<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y48_zkbcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:jump-action" /></template>
<style>
.y48_zkbcr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.061 4.061l4.525 4.525A.828.828 0 0 1 17 10h-.5a1.5 1.5 0 0 0-1.5 1.5v4a1.5 1.5 0 0 1-1.5 1.5h-3A1.5 1.5 0 0 1 9 15.5v-4A1.5 1.5 0 0 0 7.5 10H7a.828.828 0 0 1-.586-1.414l4.525-4.525a1.5 1.5 0 0 1 2.122 0M3.5 21h17");
}

</style>
