<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ohr9_dbpq"/><path class="qv9gt_89n"/><path class="t2wkaacnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carbon-cycle" /></template>
<style>
.ohr9_dbpq {
  d: path("M3.5 8.25a8 8 0 0 1 15 0");
}

.qv9gt_89n {
  d: path("m20 5l-1.5 3.25l-3.25-1.5M9.613 18.845q-.257-.045-.51-.107t-.501-.14t-.491-.172t-.479-.203t-.465-.235t-.448-.264t-.431-.293q-.21-.153-.41-.32q-.2-.166-.389-.346t-.365-.37t-.341-.394q-.164-.202-.314-.415t-.287-.434t-.257-.452q-.122-.231-.228-.468T3.5 13.75");
}

.t2wkaacnr {
  d: path("m2 17l1.5-3.25l3.25 1.5m8 6.25a2.25 2.25 0 0 1-.25-4.5a3 3 0 0 1 5.5 0a2.5 2.5 0 0 1-.5 4.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
