<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbnuuul9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:internal-job-board" /></template>
<style>
.tbnuuul9h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.328 21.5H2.5V6q0-.098.019-.195t.057-.188t.093-.173q.054-.081.124-.151t.151-.124q.082-.055.173-.093t.188-.057T3.5 5H6V2.5h4V5h2.5q.098 0 .195.019t.188.057t.173.093t.151.124t.124.151t.093.173t.057.188T13.5 6v1.472M5.25 8.5H6.5m2.75 0h1.25m-5.25 3.25H6.5m-1.25 3.5H6.5m-1.25 3.5H6.5M13.25 13h7a1.25 1.25 0 0 1 1.25 1.25v6a1.25 1.25 0 0 1-1.25 1.25h-7A1.25 1.25 0 0 1 12 20.25v-6A1.25 1.25 0 0 1 13.25 13Zm1.5 3h4m-4 2.75h2.75m-.25-7.5V13m-1-2.75a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
