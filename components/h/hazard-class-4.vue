<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yh3o8-b_d"/><path class="t257n8_qu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hazard-class-4" /></template>
<style>
.t257n8_qu {
  d: path("M12 6.25c1.25 2.5 3.5 3.5 3.5 6.5a3.5 3.5 0 0 1-7 0C8.5 11 9.25 10 10.25 9c.25 1.5.75 2 1.25 2.25c0-2-.5-3.5.5-5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yh3o8-b_d {
  d: path("M12 2.25L21.75 12L12 21.75L2.25 12Z");
}

</style>
