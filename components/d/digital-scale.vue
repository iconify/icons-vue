<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wre4swbhy"/><path class="u6ybrabrx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:digital-scale" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u6ybrabrx {
  d: path("M9.375 11.75h5.25A1.375 1.375 0 0 1 16 13.125a1.375 1.375 0 0 1-1.375 1.375h-5.25A1.375 1.375 0 0 1 8 13.125a1.375 1.375 0 0 1 1.375-1.375M5.5 17.25V19m13-1.75V19");
}

.wre4swbhy {
  d: path("M6 5.5h12L21.5 9v6.75a1.5 1.5 0 0 1-1.5 1.5H4a1.5 1.5 0 0 1-1.5-1.5V9ZM2.5 9h19");
}

</style>
