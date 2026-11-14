<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qnvjtkbin"/><path class="rf-qxwcmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:address-label" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qnvjtkbin {
  d: path("M4.5 5h13l4 4v8a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2");
}

.rf-qxwcmu {
  d: path("M7.5 15.5C5 13 5 12.5 5 11a2.5 2.5 0 0 1 5 0c0 1.5 0 2-2.5 4.5m5.5-5h5m-5 4h3.5");
}

</style>
