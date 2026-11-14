<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ct9o93uth"/><path class="wh65k9ual"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bike-id-tag" /></template>
<style>
.ct9o93uth {
  d: path("m3 9l4-4h12.5a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wh65k9ual {
  d: path("M6.75 9.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM12.5 9H18m-5.5 3.5h4m-10 3.25H18");
}

</style>
