<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wknjzkbcl"/><path class="hy1de4b2q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cooking-show" /></template>
<style>
.hy1de4b2q {
  d: path("M6 12h12M7.5 12v3.5a2 2 0 0 0 2 2h5a2 2 0 0 0 2-2V12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wknjzkbcl {
  d: path("M2.5 8h19v13.5h-19ZM8 3l4 5l4-5");
}

</style>
