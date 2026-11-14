<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i1xxpnvzs"/><path class="pu1vf9btx"/><path class="kap-jqbyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:envelope-print" /></template>
<style>
.i1xxpnvzs {
  d: path("M7 16H5a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-2M7 8V3h10v5");
}

.kap-jqbyq {
  d: path("m7 12.5l5 3.5l5-3.5");
}

.pu1vf9btx {
  d: path("M7 12h10v9.5H7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
