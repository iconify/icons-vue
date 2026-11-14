<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b920k0_hq"/><path class="immu4dbwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cheek-blush" /></template>
<style>
.b920k0_hq {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0ZM9 9.5h.01m5.99 0h.01");
}

.immu4dbwn {
  d: path("M13.949 15.625a2.25 2.25 0 0 1-3.898 0M5.5 13.25a1.5 1 0 1 0 3 0a1.5 1 0 1 0-3 0Zm10 0a1.5 1 0 1 0 3 0a1.5 1 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
