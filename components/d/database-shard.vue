<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pf-0bccsx"/><path class="reabgpbsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:database-shard" /></template>
<style>
.pf-0bccsx {
  d: path("M10.5 6A7.5 2.5 0 0 0 3 8.5v10a7.5 2.5 0 0 0 7.5 2.5Zm3-3A7.5 2.5 0 0 1 21 5.5v10a7.5 2.5 0 0 1-7.5 2.5Z");
}

.reabgpbsb {
  d: path("M3 8.5a7.5 2.5 0 0 0 7.5 2.5m3-3A7.5 2.5 0 0 0 21 5.5m-18 8a7.5 2.5 0 0 0 7.5 2.5m3-3a7.5 2.5 0 0 0 7.5-2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
