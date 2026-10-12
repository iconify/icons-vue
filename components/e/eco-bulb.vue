<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l4ud1wbcu"/><path class="pp5_mfb6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eco-bulb" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l4ud1wbcu {
  d: path("M7.75 12.75a5.75 5.75 0 1 1 8.5 0Zm1.25 3h6q1 0 .78.98l-.81 3.54q-.22.98-1.22.98h-3.5q-1 0-1.22-.98l-.81-3.54q-.22-.98.78-.98");
}

.pp5_mfb6c {
  d: path("M9.5 10.25c.25-2.6 1.5-3.75 5-3.75c-.25 2.6-1.5 3.75-5 3.75");
}

</style>
