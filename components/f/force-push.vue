<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0cvbfg_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:force-push" /></template>
<style>
.i0cvbfg_i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.625 13.5h8.75A2.625 2.625 0 0 1 19 16.125v2.75a2.625 2.625 0 0 1-2.625 2.625h-8.75A2.625 2.625 0 0 1 5 18.875v-2.75A2.625 2.625 0 0 1 7.625 13.5M3.5 10.75h17M12 2.5v8.25m-3-3l3 3l3-3");
}

</style>
