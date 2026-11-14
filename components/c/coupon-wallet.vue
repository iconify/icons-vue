<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l48t2m64w"/><path class="wvdgtjrwy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coupon-wallet" /></template>
<style>
.l48t2m64w {
  d: path("M2.5 10.5h19v11h-19Zm1.25 0L3.5 8.75a1.75 1.75 0 0 0-.5-3.5L2.75 3.5l11-1.5l.25 1.75a1.75 1.75 0 0 0 .5 3.5l.25 3.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wvdgtjrwy {
  d: path("M16 13.25h5.5v4H16Zm-13.5 2H16M6.75 6.5l4-.5");
}

</style>
