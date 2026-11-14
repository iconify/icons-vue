<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gonsmsbdc"/><path class="p4i731bfw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:capsule-split" /></template>
<style>
.gonsmsbdc {
  fill: currentColor;
  d: path("m9.75 9.75l-5 5a3.25 3.25 0 0 0 4.5 4.5l5-5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p4i731bfw {
  d: path("m9.75 9.75l5-5a3.25 3.25 0 0 1 4.5 4.5l-5 5Z");
}

</style>
