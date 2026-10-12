<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z_ho-nton"/><path class="y_88u5bln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:decagon" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y_88u5bln {
  d: path("M7.75 9.5L9.5 8.25v7.5m4.75-7.5c1.25 0 2 1.5 2 3.75s-.75 3.75-2 3.75s-2-1.5-2-3.75s.75-3.75 2-3.75");
}

.z_ho-nton {
  d: path("m21.05 12.48l-1.45 4.45q-.16.48-.56.77l-3.79 2.76q-.41.29-.91.29H9.66q-.5 0-.91-.29L4.96 17.7q-.4-.29-.56-.77l-1.45-4.45q-.15-.48 0-.96L4.4 7.07q.16-.48.56-.77l3.79-2.76q.41-.29.91-.29h4.68q.5 0 .91.29l3.79 2.76q.4.29.56.77l1.45 4.45q.15.48 0 .96");
}

</style>
