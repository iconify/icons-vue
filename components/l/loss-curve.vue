<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qmvt8fbnf"/><path class="dmq7ty1vb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:loss-curve" /></template>
<style>
.dmq7ty1vb {
  d: path("M7 4.75C8.5 12.25 11.5 16 20.25 16.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qmvt8fbnf {
  d: path("M3.25 3.25v17.5h17.5");
}

</style>
