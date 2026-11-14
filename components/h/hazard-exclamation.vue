<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="az-zfzbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hazard-exclamation" /></template>
<style>
.az-zfzbow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.712 6.212l2.076 2.076a5.25 5.25 0 0 1 0 7.424l-2.076 2.076a5.25 5.25 0 0 1-7.424 0l-2.076-2.076a5.25 5.25 0 0 1 0-7.424l2.076-2.076a5.25 5.25 0 0 1 7.424 0M12 7.5v5.25m0 3.5h.01");
}

</style>
