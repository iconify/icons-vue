<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jp7hvd4yn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:caret-down" /></template>
<style>
.jp7hvd4yn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.901 15.316l-3.06-3.295A1.5 1.5 0 0 1 8.94 9.5h6.12a1.5 1.5 0 0 1 1.099 2.521l-3.06 3.295a1.5 1.5 0 0 1-2.198 0");
}

</style>
