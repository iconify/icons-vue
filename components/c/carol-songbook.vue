<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yusw6cykf"/><path class="a7yq-8xrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carol-songbook" /></template>
<style>
.a7yq-8xrq {
  d: path("M14.75 14.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm3 0V8.5l1.25 1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yusw6cykf {
  d: path("M12 6c-2-2-6-2.5-9.5-2v15c3.5-.5 7.5 0 9.5 2m0-15c2-2 6-2.5 9.5-2v15c-3.5-.5-7.5 0-9.5 2m0-15v15");
}

</style>
