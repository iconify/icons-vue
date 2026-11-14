<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ibqgnq3co"/><path class="qtuyzdb0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:basketball-pass-bounce" /></template>
<style>
.ibqgnq3co {
  d: path("M11 7a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm0 0h9");
}

.qtuyzdb0d {
  d: path("M12.25 3.75q3.25 3.25 0 6.5m6.5-6.5q-3.25 3.25 0 6.5M2.5 21h19M3 4l5 13.5l3.5-5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
