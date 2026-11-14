<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h868ntb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dual-arm-robot" /></template>
<style>
.h868ntb-y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 4.5h3a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-3a2 2 0 0 1-2-2a2 2 0 0 1 2-2m1.5-2v2m-1.875 6.75h3.75a2.625 2.625 0 0 1 2.625 2.625v4.5A2.625 2.625 0 0 1 13.875 21h-3.75A2.625 2.625 0 0 1 7.5 18.375v-4.5a2.625 2.625 0 0 1 2.625-2.625M7.5 13.5l-3 3l-2-4.5m14 1.5l3 3l2-4.5");
}

</style>
