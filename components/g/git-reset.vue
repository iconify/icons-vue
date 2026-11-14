<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="apr4zmbhp"/><path class="ra-eob2dr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:git-reset" /></template>
<style>
.apr4zmbhp {
  d: path("M19 3v4.5a4.5 4.5 0 0 1-4.5 4.5H11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ra-eob2dr {
  d: path("M13.5 9.5L11 12l2.5 2.5M6 3v6.75M3.75 12a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M6 14.25V21");
}

</style>
