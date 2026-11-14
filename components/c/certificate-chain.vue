<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xllc3vb4v"/><path class="f263qbc5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:certificate-chain" /></template>
<style>
.f263qbc5n {
  d: path("m15.745 17.134l3.889-3.889l2.121 2.121l-3.889 3.889Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xllc3vb4v {
  d: path("M11.4 17.5H2.5v-14h17v5.9M6 7.5h10M6 11h5m2.245 8.634l3.889-3.889l2.121 2.121l-3.889 3.889Z");
}

</style>
