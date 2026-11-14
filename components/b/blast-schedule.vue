<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xjrv2lbyu"/><path class="wv_f1_zyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blast-schedule" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wv_f1_zyg {
  d: path("M15.75 15.25L13.5 16l1.25 2l-2-1l-.75 2l-.75-2l-2 1l1.25-2l-2.25-.75l2.25-.75l-1.25-2l2 1l.75-2l.75 2l2-1l-1.25 2Z");
}

.xjrv2lbyu {
  d: path("M3 4h18v17.5H3Zm0 4.5h18m-13-6v3m8-3v3");
}

</style>
