<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ettgj0m8o"/><path class="pbik6qbqu"/><path class="g_gti4baf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:delivery-bicycle" /></template>
<style>
.ettgj0m8o {
  d: path("M3 17.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m11.5 0a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

.g_gti4baf {
  d: path("m17.75 17.5l-2-8.5H18M5.25 4.5h4A1.75 1.75 0 0 1 11 6.25v2.5a1.75 1.75 0 0 1-1.75 1.75h-4A1.75 1.75 0 0 1 3.5 8.75v-2.5A1.75 1.75 0 0 1 5.25 4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pbik6qbqu {
  d: path("M6.25 17.5h5.25L16 10m-4.5 7.5l-2-7");
}

</style>
