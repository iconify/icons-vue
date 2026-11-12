<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tbl4j-bom"/><path class="gnrb8ib6h"/><path class="mvx2c_b9q"/><path class="ko6o-6b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:confounded-circle-broken" /></template>
<style>
.gnrb8ib6h {
  stroke-linejoin: round;
  d: path("M16 12L14 10.5L16 9");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ko6o-6b9b {
  d: path("M7 3.33782C8.47087 2.48697 10.1786 2 12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 10.1786 2.48697 8.47087 3.33782 7");
}

.mvx2c_b9q {
  stroke-linejoin: round;
  d: path("M15 16L14 15L13 16L12 15L11 16L10 15L9 16");
}

.tbl4j-bom {
  stroke-linejoin: round;
  d: path("M8 12L10 10.5L8 9");
}

</style>
