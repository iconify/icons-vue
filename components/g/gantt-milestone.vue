<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea3y9qbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gantt-milestone" /></template>
<style>
.ea3y9qbzh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 5h4A2.25 2.25 0 0 1 11 7.25A2.25 2.25 0 0 1 8.75 9.5h-4A2.25 2.25 0 0 1 2.5 7.25A2.25 2.25 0 0 1 4.75 5m4.5 10h10a2.25 2.25 0 0 1 2.25 2.25a2.25 2.25 0 0 1-2.25 2.25h-10A2.25 2.25 0 0 1 7 17.25A2.25 2.25 0 0 1 9.25 15m9.311-10.189l1.378 1.378a1.5 1.5 0 0 1 0 2.122l-1.378 1.378a1.5 1.5 0 0 1-2.122 0l-1.378-1.378a1.5 1.5 0 0 1 0-2.122l1.378-1.378a1.5 1.5 0 0 1 2.122 0");
}

</style>
