<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b4bwb9mdn"/><path class="vck1iacwt"/><path class="ayn8d5hzc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-er" /></template>
<style>
.ayn8d5hzc {
  d: path("M3 9.5a5 2 0 0 0 10 0M8 16v2.5h7.75m0-3.25h6v6h-6Z");
}

.b4bwb9mdn {
  d: path("M3 5a5 2 0 1 0 10 0A5 2 0 1 0 3 5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vck1iacwt {
  d: path("M3 5v9a5 2 0 0 0 10 0V5");
}

</style>
