<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xkna8_buo"/><path class="okqytyb5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:free-gift-wrap" /></template>
<style>
.okqytyb5t {
  d: path("M12 6c0-3-3.5-3-3-1c.5 1.5 3 1 3 1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xkna8_buo {
  d: path("M3.5 9.5h17v11h-17ZM2.5 6h19v3.5h-19ZM12 6v14.5");
}

</style>
