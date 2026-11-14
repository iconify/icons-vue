<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vg434_voi"/><path class="ebisy4seg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:diaper-cloth" /></template>
<style>
.ebisy4seg {
  d: path("M5.5 7.75H10v2.5H5.5Zm8.5 0h4.5v2.5H14Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vg434_voi {
  d: path("M2.5 5h19v6.5c-3 .5-5.5 3-6 7.5h-7c-.5-4.5-3-7-6-7.5Z");
}

</style>
