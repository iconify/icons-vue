<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs1xtxl9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:carpenter-pencil" /></template>
<style>
.fs1xtxl9e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.48 4.045l2.475 2.475a1.75 1.75 0 0 1 0 2.475l-6.718 6.717a1.75 1.75 0 0 1-2.474 0l-2.475-2.475a1.75 1.75 0 0 1 0-2.474l6.717-6.718a1.75 1.75 0 0 1 2.475 0m-8.915 9.469l1.921 1.921a1.5 1.5 0 0 1-.427 2.42l-2.41 1.125a1.5 1.5 0 0 1-1.695-.298l-.636-.636a1.5 1.5 0 0 1-.298-1.695l1.125-2.41a1.5 1.5 0 0 1 2.42-.427m-2.222 2.729l1.414 1.414");
}

</style>
