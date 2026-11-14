<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nxaihbbaq"/><path class="a5fsbcbix"/><path class="xsz8hrbvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:confidence-interval" /></template>
<style>
.a5fsbcbix {
  fill: currentColor;
  d: path("M8.5 19.5V9.25C9.5 6 10.5 4 12 4s2.5 2 3.5 5.25V19.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nxaihbbaq {
  d: path("M2.5 19.5C7 19.5 8.5 4 12 4s5 15.5 9.5 15.5");
}

.xsz8hrbvx {
  d: path("M2.5 19.5h19");
}

</style>
