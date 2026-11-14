<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wuixsugxy"/><path class="cm7x2xb1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab-notebook" /></template>
<style>
.cm7x2xb1v {
  d: path("M11 6h3v2l2 5H9l2-5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wuixsugxy {
  d: path("M5 18.5V5a2 2 0 0 1 2-2h12v13.5H7a2 2 0 0 0 0 4h12");
}

</style>
