<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="dnp2npbye"/><path class="lp74xqzru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:elevator-sign" /></template>
<style>
.dnp2npbye {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 2.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lp74xqzru {
  d: path("m12.47 6.59l2.06 2.57q.47.59-.28.59h-4.5q-.75 0-.28-.59l2.06-2.57q.47-.59.94 0m-2.72 7.66h4.5q.75 0 .28.59l-2.06 2.57q-.47.59-.94 0l-2.06-2.57q-.47-.59.28-.59");
}

</style>
