<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xxqg8v1if"/><path class="oyw-6qbnh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leaf-bag" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oyw-6qbnh {
  d: path("M8.75 17.75c0-4.25 2.5-6.75 6.5-6.75c0 4.25-2.5 6.75-6.5 6.75");
}

.xxqg8v1if {
  d: path("M7.431 8h9.138a2.625 2.625 0 0 1 2.617 2.424l.597 7.75A2.625 2.625 0 0 1 17.165 21H6.835a2.625 2.625 0 0 1-2.618-2.826l.597-7.75A2.625 2.625 0 0 1 7.431 8M9 8V6.5a3 3 0 0 1 6 0V8");
}

</style>
