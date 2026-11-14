<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v0dzfzbhx"/><path class="ig69czf0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:clarity" /></template>
<style>
.ig69czf0c {
  fill: currentColor;
  d: path("m12 3l-9 9l9 9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v0dzfzbhx {
  d: path("m12 3l9 9l-9 9l-9-9Z");
}

</style>
