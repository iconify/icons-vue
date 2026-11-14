<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="msatfabgr"/><path class="jxa8v5bhe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bank-counter" /></template>
<style>
.jxa8v5bhe {
  d: path("m17.5 17.5l1-.75v2.75");
}

.msatfabgr {
  d: path("M12.4 12.5H2.5V10h19v2.4m-9.1 8.1H3.5v-8h8.9m-.4 0v8m3.25-5.25h6.25v6.25h-6.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
