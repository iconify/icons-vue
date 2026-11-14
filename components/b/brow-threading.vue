<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k5xg39bwq"/><path class="g-u32e0rk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:brow-threading" /></template>
<style>
.g-u32e0rk {
  d: path("M3 17c4 4 6 4 9 0s5-4 9 0");
}

.k5xg39bwq {
  d: path("M2.5 11.5c3-7 11.5-10 19-4.5c-7.5-1-14 1-19 4.5ZM3 17c4-4 6-4 9 0s5 4 9 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
