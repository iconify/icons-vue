<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uvan74bwi"/><path class="pxg4flwco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:double-alt-arrow-left-linear" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pxg4flwco {
  d: path("M16.9998 18.9999L10.9998 11.9999L16.9998 4.99988");
}

.uvan74bwi {
  d: path("M12.9999 19L6.99989 12L12.9999 5");
}

</style>
