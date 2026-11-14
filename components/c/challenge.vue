<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kx8ydsb6b"/><path class="wervzqb-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:challenge" /></template>
<style>
.kx8ydsb6b {
  d: path("M7 3.5h10V9A5 5 0 0 1 7 9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wervzqb-p {
  d: path("M7 5.5H4c0 3.5 1.5 5 3.5 5.5M17 5.5h3c0 3.5-1.5 5-3.5 5.5M12 14v6.5m-4 0h8");
}

</style>
