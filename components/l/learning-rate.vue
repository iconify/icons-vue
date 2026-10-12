<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qmvt8fbnf"/><path class="jqmpoif4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:learning-rate" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jqmpoif4s {
  d: path("M6.75 6.25h4v5h4v4.5h5");
}

.qmvt8fbnf {
  d: path("M3.25 3.25v17.5h17.5");
}

</style>
