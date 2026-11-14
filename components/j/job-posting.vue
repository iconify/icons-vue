<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o0uxpabcc"/><path class="rh969fgqv"/><path class="xliw16qtn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:job-posting" /></template>
<style>
.o0uxpabcc {
  d: path("M2.5 3.5h19v17h-19Z");
}

.rh969fgqv {
  d: path("M7 8h10v9H7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xliw16qtn {
  d: path("M10.5 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-1 3.5h5m-5 2.75H13");
}

</style>
