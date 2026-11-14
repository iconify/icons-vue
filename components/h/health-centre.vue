<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zmd0gnfrv"/><path class="v9qiwoomi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:health-centre" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v9qiwoomi {
  d: path("M9 8h1.25L11 6.5l1.25 3L13 8h2m-5 13.5v-6h4v6m-9-9h.01m-.01 4h.01m13.99-4h.01m-.01 4h.01");
}

.zmd0gnfrv {
  d: path("M2.5 21.5V9h5V4.5h9V9h5v12.5Z");
}

</style>
