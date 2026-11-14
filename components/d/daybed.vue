<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p73xu4bns"/><path class="cnvmw8ouh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:daybed" /></template>
<style>
.cnvmw8ouh {
  d: path("M5.25 9h4.5v3h-4.5Z");
}

.p73xu4bns {
  d: path("M2.5 19V6h19v13m-19-7h19m-19 4h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
