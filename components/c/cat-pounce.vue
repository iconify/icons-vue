<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gn_73vq8g"/><path class="jzp_zcb-g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cat-pounce" /></template>
<style>
.gn_73vq8g {
  d: path("M7 9.5c3 0 6 1.5 8.5 2.75l1-2.25l1.25 2l1.5-1l.5 2.75c1 1.5.25 3-1.5 3H9.5c-2.5 0-4-2.25-3.75-4.75c.1-1.5.5-2.5 1.25-2.5Z");
}

.jzp_zcb-g {
  d: path("M6.25 10.25C4 9 3 6.5 4 3.5m4 13.25L6.5 20m9.5-3.25l3 3m-1.75-6h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
