<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ibdmb-bqs"/><path class="pvw5z8bxn"/><path class="a6yqt2buc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hoa-rules" /></template>
<style>
.a6yqt2buc {
  d: path("M11.5 14v-2.5h2V14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ibdmb-bqs {
  d: path("M4.5 19.25V5A2.5 2.5 0 0 1 7 2.5h12.5V17H6.75a2.25 2.25 0 0 0 0 4.5H19.5");
}

.pvw5z8bxn {
  d: path("M10.5 4.75h4a1.5 1.5 0 0 1 1.5 1.5v6.25a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 9 12.5V6.25a1.5 1.5 0 0 1 1.5-1.5M11 7.5h.01m2.99 0h.01");
}

</style>
