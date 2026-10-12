<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="swr0-e-ae"/><path class="xt_laubzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:magic-ring-sharp" /></template>
<style>
.swr0-e-ae {
  d: path("M8.5 7.4a7.07 7.07 0 1 0 4 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xt_laubzl {
  d: path("M9.25 4.5h3l.33.38l.84.99l.33.38l-.37.34l-2.51 2.32l-.37.34l-.37-.34l-2.51-2.32l-.37-.34l.33-.38l.84-.99l.33-.38zM19 2.75l.27 1.98l1.98.27l-1.98.27L19 7.25l-.27-1.98L16.75 5l1.98-.27z");
}

</style>
