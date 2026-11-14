<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxntj7bdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hexagon" /></template>
<style>
.cxntj7bdl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.313 3.008l5.818 3.359a2.63 2.63 0 0 1 1.313 2.274v6.718a2.63 2.63 0 0 1-1.313 2.274l-5.818 3.359a2.63 2.63 0 0 1-2.625 0l-5.819-3.359a2.63 2.63 0 0 1-1.313-2.274V8.641a2.63 2.63 0 0 1 1.313-2.274l5.819-3.359a2.63 2.63 0 0 1 2.625 0");
}

</style>
