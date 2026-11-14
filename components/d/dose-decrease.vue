<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgk0pjb0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dose-decrease" /></template>
<style>
.xgk0pjb0s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 5H7v16H3.5Zm6.5 5h3.5v11H10Zm6.5 6H20v5h-3.5Zm1.75-12v8.5m-2-2l2 2l2-2");
}

</style>
