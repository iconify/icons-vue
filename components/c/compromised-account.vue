<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b0f5_q40h"/><path class="acukmzbyh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:compromised-account" /></template>
<style>
.acukmzbyh {
  d: path("m9.75 3l-1.5 3.5l2.5 2.5l-1.5 4M18 14.5V18m0 3h.01");
}

.b0f5_q40h {
  d: path("M4.25 8a5 5 0 1 0 10 0a5 5 0 1 0-10 0ZM3 21.5C3 18.25 5.5 16 9.25 16c3.016 0 5.223 1.455 5.972 3.716");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
