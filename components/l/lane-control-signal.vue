<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gx1f74b3r"/><path class="vxyaz8bbx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lane-control-signal" /></template>
<style>
.gx1f74b3r {
  d: path("M2.5 4h8v8h-8Zm11 0h8v8h-8Zm-7 8v9.5m11-9.5v9.5M5 6.5l3 3m0-3l-3 3M17.5 6v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vxyaz8bbx {
  d: path("m16 8.5l1.5 1.5L19 8.5");
}

</style>
