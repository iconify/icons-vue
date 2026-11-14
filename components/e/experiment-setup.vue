<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft7vkkboc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:experiment-setup" /></template>
<style>
.ft7vkkboc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 2.5v19m-2 0h18m-6.25-17za1.75 1.75 0 0 1 1.75 1.75v3.369a1.75 1.75 0 0 0 .158.728l2.709 5.925a1.75 1.75 0 0 1-1.591 2.478h-6.052a1.75 1.75 0 0 1-1.591-2.478l2.709-5.925A1.75 1.75 0 0 0 13 9.619V6.25a1.75 1.75 0 0 1 1.75-1.75M5 7.5h8");
}

</style>
