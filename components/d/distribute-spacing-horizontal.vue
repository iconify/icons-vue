<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwogpklst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:distribute-spacing-horizontal" /></template>
<style>
.xwogpklst {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 6h.5A1.75 1.75 0 0 1 7 7.75v8.5A1.75 1.75 0 0 1 5.25 18h-.5A1.75 1.75 0 0 1 3 16.25v-8.5A1.75 1.75 0 0 1 4.75 6m7-2.5h.5A1.75 1.75 0 0 1 14 5.25v13.5a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 10 18.75V5.25a1.75 1.75 0 0 1 1.75-1.75m7 4.5h.5A1.75 1.75 0 0 1 21 9.75v4.5A1.75 1.75 0 0 1 19.25 16h-.5A1.75 1.75 0 0 1 17 14.25v-4.5A1.75 1.75 0 0 1 18.75 8");
}

</style>
