<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="siw0-tlnx"/><path class="epiwl6bna"/><path class="usv6yclsl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-dot-plot" /></template>
<style>
.epiwl6bna {
  fill: currentColor;
  d: path("M12.75 5.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M7.25 12a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m9 6.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.siw0-tlnx {
  d: path("M2.5 5.5H5M2.5 12H5m-2.5 6.5H5");
}

.usv6yclsl {
  d: path("M8 5.5h.01m2.74 0h.01m8.74 0h.01M13.25 12h.01M16 12h.01m2.74 0h.01m2.74 0h.01M8 18.5h.01m2.74 0h.01m2.74 0h.01");
}

</style>
