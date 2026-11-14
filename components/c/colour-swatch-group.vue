<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xpnpdgapb"/><path class="up-lq3jfa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:colour-swatch-group" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.up-lq3jfa {
  d: path("M6 10.5h12V16H6Zm4 0V16m4-5.5V16");
}

.xpnpdgapb {
  d: path("M2.5 18.5v-13A1.5 1.5 0 0 1 4 4h5l2 2.5h9A1.5 1.5 0 0 1 21.5 8v10.5A1.5 1.5 0 0 1 20 20H4a1.5 1.5 0 0 1-1.5-1.5Z");
}

</style>
