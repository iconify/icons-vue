<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ohe6hmbpk"/><path class="xgnki0bsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:kids-watch" /></template>
<style>
.ohe6hmbpk {
  d: path("M7 6h10a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1Zm1.5 0L9 3h6l.5 3m-7 12l.5 3h6l.5-3m-4.75-7.5h.01m2.49 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xgnki0bsy {
  d: path("M14.114 13.02a2.25 2.25 0 0 1-4.228 0");
}

</style>
