<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qv-e6pbun"/><path class="t2n6rwamh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hen-with-chicks" /></template>
<style>
.qv-e6pbun {
  d: path("M3.5 7.5L6 6c.5-2.5 4-2.5 4.5.5l1 2.5C14 9 16 8 18 4c2.5 2 3 5.5 2 8c-1.5 2.5-5 3-9 3c-3.5 0-5.5-2.5-5-6.25Z");
}

.t2n6rwamh {
  d: path("M6.75 4.5c0-2.5 3-2.5 3 .25m-6.5 15a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm6.75 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm6.75 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
