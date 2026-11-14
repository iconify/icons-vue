<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="piqj5v7wx"/><path class="cyogezbuw"/><path class="judnzd-wr"/><path class="ebq405bqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:frame-wrap" /></template>
<style>
.cyogezbuw {
  d: path("M7 7h9v9H7Z");
}

.ebq405bqc {
  d: path("M18.25 6.75L20 5l1.75 1.75");
}

.judnzd-wr {
  d: path("M7.5 20h9a3.5 3.5 0 0 0 3.5-3.5V5");
}

.piqj5v7wx {
  d: path("M2.5 2.5H12V12H2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
