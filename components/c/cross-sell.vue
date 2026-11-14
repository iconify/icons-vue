<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dldfu8bye"/><path class="lfm6z5kzc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cross-sell" /></template>
<style>
.dldfu8bye {
  d: path("M4.25 12h5.5a1.75 1.75 0 0 1 1.75 1.75v6a1.75 1.75 0 0 1-1.75 1.75h-5.5a1.75 1.75 0 0 1-1.75-1.75v-6A1.75 1.75 0 0 1 4.25 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lfm6z5kzc {
  d: path("M7.5 12V3.5q0-.098.019-.195t.057-.188t.093-.173t.124-.151t.151-.124t.173-.093t.188-.057T8.5 2.5h12q.098 0 .195.019t.188.057t.173.093q.081.054.151.124t.124.151q.055.082.093.173t.057.188t.019.195V13q0 .089-.016.177t-.047.172q-.031.083-.076.16q-.046.077-.104.144q-.058.068-.128.124q-.069.056-.147.099t-.163.072t-.173.041M15.343 14H11.5m-4-7.5h14m-7-4v4m-12 9h9M6 12v3.5m12-.5v6m-3-3h6");
}

</style>
