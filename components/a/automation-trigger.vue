<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqapg753u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:automation-trigger" /></template>
<style>
.kqapg753u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.816 5.86l-2.954 4.544A1.357 1.357 0 0 0 6 12.5h.545a1.75 1.75 0 0 1 1.739 1.943L8 17a1.051 1.051 0 0 0 1.931.68l3.227-5.071A1.372 1.372 0 0 0 12 10.5h-.637a1.75 1.75 0 0 1-1.747-1.859L9.75 6.5a1.053 1.053 0 0 0-1.934-.64M15 15.5h6m-2.25-2.25L21 15.5l-2.25 2.25");
}

</style>
