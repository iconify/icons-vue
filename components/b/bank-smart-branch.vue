<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q45tak3zi"/><path class="dd8qssbwg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bank-smart-branch" /></template>
<style>
.dd8qssbwg {
  d: path("m9.75 7.5l1.418-.945a1.5 1.5 0 0 1 1.664 0l1.418.945a.819.819 0 0 1-.454 1.5h-3.592a.819.819 0 0 1-.454-1.5M9 9v4.5M12 9v4.5M15 9v4.5m-7.5 0h9M12 18h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q45tak3zi {
  d: path("M7.875 2.5h8.25A4.375 4.375 0 0 1 20.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-8.25A4.375 4.375 0 0 1 3.5 17.125V6.875A4.375 4.375 0 0 1 7.875 2.5");
}

</style>
