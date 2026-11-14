<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zp5uwxegi"/><path class="zuo752-mb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:graduate-program" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zp5uwxegi {
  d: path("m12 5l9 4.5l-9 4.5l-9-4.5Z");
}

.zuo752-mb {
  d: path("M7 12v4.5c1.5 1.25 3.25 1.75 5 1.75s3.5-.5 5-1.75V12m3-2v5");
}

</style>
