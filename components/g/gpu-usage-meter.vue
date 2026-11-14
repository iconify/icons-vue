<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h4ubidbhr"/><path class="d88pmqbfu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gpu-usage-meter" /></template>
<style>
.d88pmqbfu {
  d: path("M8.5 13a3.5 3.5 0 0 1 7 0M12 13l2-2.25");
}

.h4ubidbhr {
  d: path("M6 5.5h12A3.5 3.5 0 0 1 21.5 9v4a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 13V9A3.5 3.5 0 0 1 6 5.5m0 11v3h7v-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
