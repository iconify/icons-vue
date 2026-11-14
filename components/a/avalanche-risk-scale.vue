<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrjni41xj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:avalanche-risk-scale" /></template>
<style>
.qrjni41xj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 17.5h-10l6-14l3.5 7L14.5 7l2 2.75m3.092 6.482l1.275 2.79a1.75 1.75 0 0 1-1.591 2.478h-2.552a1.75 1.75 0 0 1-1.591-2.478l1.275-2.79a1.75 1.75 0 0 1 3.184 0M18 16.75V19");
}

</style>
