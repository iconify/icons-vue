<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mlvvklb0x"/><path class="ktymb6zzc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:address-book" /></template>
<style>
.ktymb6zzc {
  d: path("M10.75 13.75s-3-2.25-3-5a3 3 0 0 1 6 0c0 2.75-3 5-3 5ZM3.5 19A2.5 2.5 0 0 1 6 16.5h12");
}

.mlvvklb0x {
  d: path("M3.5 19V5A2.5 2.5 0 0 1 6 2.5h12v19H6A2.5 2.5 0 0 1 3.5 19ZM18 5.5h2.75v3.75H18Zm0 6.5h2.75v3.75H18Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
