<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xoncq8-nk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bumper" /></template>
<style>
.xoncq8-nk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11h19v3.5a3 3 0 0 1-3 3h-13a3 3 0 0 1-3-3ZM7 17.5v3m10-3v3M4.5 11l2-6.5h11l2 6.5m-10 3.25h5");
}

</style>
