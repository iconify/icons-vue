<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p1u9vubjo"/><path class="qojv_-bmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:demolition" /></template>
<style>
.p1u9vubjo {
  d: path("M12.5 6h9v15.5h-9Zm-9 8.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm.5-12l2.5 9");
}

.qojv_-bmk {
  d: path("m17 6l-1.25 4L18 13l-1.5 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
