<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="l0r7vlbov"/><circle class="a7q8jib6e"/><circle class="qo9rs7j5k"/><circle class="nlor3-bpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dividend" /></template>
<style>
.a7q8jib6e {
  cx: 12px;
  cy: 7.25px;
  r: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l0r7vlbov {
  cx: 12px;
  cy: 7.25px;
  r: 4.5px;
}

.nlor3-bpa {
  cx: 17.75px;
  cy: 17.5px;
  r: 3.25px;
}

.qo9rs7j5k {
  cx: 6.25px;
  cy: 17.5px;
  r: 3.25px;
}

</style>
