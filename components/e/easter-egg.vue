<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sxbto7b4t"/><path class="d5i8a23ei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:easter-egg" /></template>
<style>
.d5i8a23ei {
  d: path("m5.25 12.25l2.25-2l2.25 2.5l2.25-2.5l2.25 2.5l2.25-2.5l2.25 2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sxbto7b4t {
  d: path("M12 2.5c-4.5 0-7 7-7 11.5s3 7.5 7 7.5s7-3 7-7.5s-2.5-11.5-7-11.5");
}

</style>
