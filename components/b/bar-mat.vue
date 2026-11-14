<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j-by4ebra"/><path class="tke87zbiw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bar-mat" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j-by4ebra {
  d: path("M7.83 4h9.905a2.625 2.625 0 0 1 2.464 3.532l-1.566 4.25A2.625 2.625 0 0 1 16.17 13.5H6.265a2.625 2.625 0 0 1-2.464-3.532l1.566-4.25A2.625 2.625 0 0 1 7.83 4");
}

.tke87zbiw {
  d: path("M9.731 6.75h5.836a1.428 1.428 0 0 1 1.308 2l-.482 1.101a1.5 1.5 0 0 1-1.374.899H9.183a1.428 1.428 0 0 1-1.308-2l.482-1.101a1.5 1.5 0 0 1 1.374-.899m9.019 9.75c1 1.25 1.75 2.25 1.75 3.25a1.75 1.75 0 0 1-3.5 0c0-1 .75-2 1.75-3.25");
}

</style>
