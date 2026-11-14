<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hzoucoxxw"/><path class="dprl56bws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:interview-no-show" /></template>
<style>
.dprl56bws {
  d: path("M18 16v2l1.5 1");
}

.hzoucoxxw {
  d: path("m2.635 3.535l4.431-.781l1.65 9.355l-4.432.782ZM6.5 12.5l1 1m4.3 3.5H3.5v-3.5h10.1M9.5 17v2m-5 2.25l5-2.25l2.569 1.156M14.5 18a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
