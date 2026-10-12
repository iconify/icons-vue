<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rfz_djb8q"/><circle class="jhtbhmnge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:field-hockey" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jhtbhmnge {
  cx: 17px;
  cy: 18.5px;
  r: 2.25px;
}

.rfz_djb8q {
  d: path("m17.25 2.75l-8 14.5a2.75 2.75 0 0 1-5-2.25");
}

</style>
