<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="csndrfvuz"/><path class="sgd2xxb1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:grandmother" /></template>
<style>
.csndrfvuz {
  d: path("M10.37 5.9a2 2 0 1 1 3.26 0a3.5 3.5 0 1 1-3.26 0M5.25 21.25v-.5a6.75 5.5 0 0 1 13.5 0v.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sgd2xxb1h {
  d: path("m9.5 17.75l2.5 2l2.5-2");
}

</style>
