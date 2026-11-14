<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uh1ab-bsl"/><path class="mjofdwb5j"/><path class="kfiurxo-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:card-joker" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kfiurxo-c {
  d: path("M6.5 10.25a1 1 0 1 0 2 0a1 1 0 1 0-2 0M11 7a1 1 0 1 0 2 0a1 1 0 1 0-2 0m4.5 3.25a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

.mjofdwb5j {
  d: path("M8.75 17q-.5-4.5-1.25-6.75q3 .25 4.5-3.25q1.5 3.5 4.5 3.25q-.75 2.25-1.25 6.75Z");
}

.uh1ab-bsl {
  d: path("M7.5 2.5h9A3.5 3.5 0 0 1 20 6v12a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 18V6a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
