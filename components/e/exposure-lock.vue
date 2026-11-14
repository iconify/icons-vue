<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_13_dbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:exposure-lock" /></template>
<style>
.m_13_dbfk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 10a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM10 2.5V4m-7.5 6H4m.75-5.25l1 1m9.5-1l-1 1m-9.5 9.5l1-1M14.5 16h7v5.5h-7Zm1.5 0v-1.25a2 2 0 0 1 4 0V16");
}

</style>
