<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="elh9u9b0h"/><path class="qg_dtcc0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:file-receipt" /></template>
<style>
.elh9u9b0h {
  d: path("M7 2.5h6.5l6 6v13L17 20.25l-2.5 1.25l-2.5-1.25l-2.5 1.25L7 20.25L4.5 21.5V5A2.5 2.5 0 0 1 7 2.5Z");
}

.qg_dtcc0b {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4m-11 3h7m-7 3.5H13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
