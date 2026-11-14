<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6slbcbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:known-issue" /></template>
<style>
.k6slbcbeg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.055 8.967l3.535 6.326a3.5 3.5 0 0 1-3.055 5.207h-7.07a3.5 3.5 0 0 1-3.055-5.207l3.535-6.326a3.5 3.5 0 0 1 6.11 0M12 10v4m0 3.25h.01");
}

</style>
