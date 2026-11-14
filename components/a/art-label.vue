<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p2wsm_bqo"/><path class="j8jq_obvn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:art-label" /></template>
<style>
.j8jq_obvn {
  d: path("M6.75 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5.75-2H18m-5.5 4H16");
}

.p2wsm_bqo {
  d: path("M8.5 5H19a2.5 2.5 0 0 1 2.5 2.5v9A2.5 2.5 0 0 1 19 19H8.5l-6-7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
