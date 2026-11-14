<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mynxxlt_u"/><path class="yls304xxg"/><path class="q8urhzb3h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:consent" /></template>
<style>
.mynxxlt_u {
  d: path("M7 5.5h10a4.5 4.5 0 0 1 4.5 4.5v4a4.5 4.5 0 0 1-4.5 4.5H7A4.5 4.5 0 0 1 2.5 14v-4A4.5 4.5 0 0 1 7 5.5Z");
}

.q8urhzb3h {
  d: path("m13.5 12.25l1 1l1.75-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yls304xxg {
  d: path("M11 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

</style>
