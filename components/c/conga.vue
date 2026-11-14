<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p_wh_ebtx"/><path class="ocr8deb-g"/><path class="jdqs-2bfp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:conga" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jdqs-2bfp {
  d: path("M5.75 9q6.25 2.5 12.5 0");
}

.ocr8deb-g {
  d: path("M6.5 5C5 10 5.5 16 8 21.5h8C18.5 16 19 10 17.5 5");
}

.p_wh_ebtx {
  d: path("M6.5 5a5.5 2 0 1 0 11 0a5.5 2 0 1 0-11 0");
}

</style>
