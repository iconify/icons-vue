<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pnvn4uvom"/><path class="emzd9efec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-card" /></template>
<style>
.emzd9efec {
  d: path("M7 11h10v6.5H7Zm5 0v6.5m-5-3.25h10");
}

.pnvn4uvom {
  d: path("M2.5 3.5h19v17h-19Zm4 4h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
