<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gpujzb-ku"/><path class="tycvu4bkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:machine-manual" /></template>
<style>
.gpujzb-ku {
  d: path("M21.5 13.081V4.5C18 4 14 4.5 12 6.5c-2-2-6-2.5-9.5-2V18c3.5-.5 7.5 0 9.5 2q.308-.307.676-.568M12 6.5V20");
}

.tycvu4bkm {
  d: path("m19 14.5l-1.75 1.75l2.5 2.5L21.5 17m-3 .5l-3.25 3.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
