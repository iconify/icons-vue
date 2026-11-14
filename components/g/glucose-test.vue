<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fshtepbwx"/><path class="ulbgdr79k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:glucose-test" /></template>
<style>
.fshtepbwx {
  d: path("M7.5 21.5V17a4.5 4.5 0 0 1 9 0v4.5");
}

.ulbgdr79k {
  fill: currentColor;
  d: path("m12 3l2.25 3a2.5 2.5 0 1 1-4.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
