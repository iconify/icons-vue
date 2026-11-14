<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wre4swbhy"/><path class="jt_ubmb4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:digital-scale" /></template>
<style>
.jt_ubmb4h {
  d: path("M8 11.75h8v2.75H8Zm-2.5 5.5V19m13-1.75V19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wre4swbhy {
  d: path("M6 5.5h12L21.5 9v6.75a1.5 1.5 0 0 1-1.5 1.5H4a1.5 1.5 0 0 1-1.5-1.5V9ZM2.5 9h19");
}

</style>
