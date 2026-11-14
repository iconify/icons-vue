<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ei1kdh0ok"/><path class="n8eb37-va"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dimension-table" /></template>
<style>
.ei1kdh0ok {
  d: path("M3 3h18v18H3Zm0 8h18M3 16h18m-10.5-5v10");
}

.n8eb37-va {
  d: path("m6.5 7l2-2h8v4h-8l-2-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
