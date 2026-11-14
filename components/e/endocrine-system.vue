<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ip99hrbii"/><path class="jt35ztbci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:endocrine-system" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ip99hrbii {
  d: path("M11.936 19.5h-.686c-.5 0-1-.5-1-1L10 15a.781.781 0 0 0-1.5 0l-.25 3.5c0 .5-.5 1-1 1h-1c-.75 0-1.25-.5-1-1.25L6 14l.5-2l-1.25 1.5c-.25.5-.5.75-1.25.75c-1 0-1.5-.5-1.25-1.5l2-2.5C5 9 6 8.75 7.25 8.75h4c1.25 0 2.25.25 2.5 1.5l1.781 2.226m-2.122 1.302a3 3 0 0 1-.159-.278L12 12l.5 2l.119.675M7.25 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0m11.5 10.433l1.748 1.009a1.5 1.5 0 0 1 .75 1.299v2.018a1.5 1.5 0 0 1-.75 1.299l-1.748 1.009a1.5 1.5 0 0 1-1.5 0l-1.748-1.009a1.5 1.5 0 0 1-.75-1.299v-2.018a1.5 1.5 0 0 1 .75-1.299l1.748-1.009a1.5 1.5 0 0 1 1.5 0");
}

.jt35ztbci {
  fill: currentColor;
  d: path("M17 18a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
