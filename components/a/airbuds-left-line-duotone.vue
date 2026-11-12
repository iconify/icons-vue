<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ubwfpy16r"/><path class="e-jucopue"/><circle class="k0oipm7yh"/><path class="a_mtj062n"/><path class="uwb6dhb5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:airbuds-left-line-duotone" /></template>
<style>
.a_mtj062n {
  stroke-linejoin: round;
  d: path("M14 14V19H17");
}

.e-jucopue {
  d: path("M8 5V8");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k0oipm7yh {
  cx: 15.5px;
  cy: 16.5px;
  r: 5.5px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ubwfpy16r {
  d: path("M2 18.6667V19.5C2 20.8807 3.11929 22 4.5 22C5.88071 22 7 20.8807 7 19.5V18.6667M2 18.6667V7.625L2.00007 7.55936C2.01591 4.49563 4.49563 2.01591 7.55936 2.00007L7.625 2L7.66438 2.00004C9.50262 2.00954 10.9905 3.49738 11 5.33562L11 5.375V8C11 9.65685 9.65685 11 8 11C7.44772 11 7 11.4477 7 12V18.6667M2 18.6667H7");
}

.uwb6dhb5x {
  d: path("M17.9009 8.99999C17.5032 7.04086 15.96 5.49769 14.0009 5.10001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
