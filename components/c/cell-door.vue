<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lh24_ubkm"/><path class="sye78vbzq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cell-door" /></template>
<style>
.lh24_ubkm {
  d: path("M12.2 21.5H3v-19h15v9m-10-9v19m5-19v11.7m2 2.8h6v4.5h-6Z");
}

.sye78vbzq {
  d: path("M16.25 17v-1a1.75 1.75 0 0 1 3.5 0v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
