<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tlzx4-yio"/><path class="ayxegbxku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:body-scan-meditation" /></template>
<style>
.ayxegbxku {
  d: path("M6.5 16.25c0-1.25 2-2 5.5-2s5.5.75 5.5 2c0 .75-.5 1.25-1.5 1.25H8c-.75 0-1.5-.5-1.5-1.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tlzx4-yio {
  d: path("M3.5 8V6A2.5 2.5 0 0 1 6 3.5h2m8 0h2A2.5 2.5 0 0 1 20.5 6v2m0 8v2a2.5 2.5 0 0 1-2.5 2.5h-2m-8 0H6A2.5 2.5 0 0 1 3.5 18v-2m7-8.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-1.5 7c0-2.5 1.5-3.75 3-3.75c1.75 0 3 1.25 3 3.75");
}

</style>
