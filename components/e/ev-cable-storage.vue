<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d2tx-bb_e"/><path class="f6yu1pbhq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ev-cable-storage" /></template>
<style>
.d2tx-bb_e {
  d: path("M2.5 9.5a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Z");
}

.f6yu1pbhq {
  d: path("M9 13a3.5 3.5 0 1 1 3.5-3.5m3 0c3 0 4 1.5 4 3.5v2M17 15h5v4h-5Zm1 4v2.5m3-2.5v2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
