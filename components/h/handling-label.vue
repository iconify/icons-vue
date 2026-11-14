<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xywvsisoo"/><path class="s2g-ribci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:handling-label" /></template>
<style>
.s2g-ribci {
  d: path("M8.75 2.5v8h4v-8m4.75 9l4.25 9.75h-8.5Zm0 4.5v3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xywvsisoo {
  d: path("M11.4 18.5H2.5v-16H19V8M2.5 8H16");
}

</style>
