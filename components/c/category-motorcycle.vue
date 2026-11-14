<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lf3v-ibsv"/><path class="kgycf273o"/><path class="dbczmxb_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-motorcycle" /></template>
<style>
.dbczmxb_z {
  d: path("M9.75 11.5h5v5h-5Zm-5 5.75l5-1.75m-5 1.75h.01m14.49 0h.01");
}

.kgycf273o {
  fill: currentColor;
  d: path("M9 10c0-2.5 3-3 5.5-1.75l1 2.25H9Z");
}

.lf3v-ibsv {
  d: path("M2 17.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm14.5 0a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm2.75 0L16.5 6.5m0 0l-2.25-2M3.5 9.5H9");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
