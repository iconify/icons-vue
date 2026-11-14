<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o0uxpabcc"/><path class="qncdlqy3p"/><path class="jd2xql-0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:brand-illustration" /></template>
<style>
.jd2xql-0s {
  d: path("m8.25 17.5l5.25-8.25l5.25 8.25Z");
}

.o0uxpabcc {
  d: path("M2.5 3.5h19v17h-19Z");
}

.qncdlqy3p {
  d: path("M6.25 10.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
