<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qnljgeszn"/><path class="o_tvdkr8v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cb-radio" /></template>
<style>
.o_tvdkr8v {
  d: path("M5.5 15a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm9-1.75h4m-4 3.5h4");
}

.qnljgeszn {
  d: path("M2.5 9h19v12h-19Zm15 0L20 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
