<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="v0rzdcctt"/><path class="jrs2wepna"/><path class="vt-vgvh_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fox-sharp" /></template>
<style>
.jrs2wepna {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 13c1.75 0 3.5.75 5 2.25c1.5-1.5 3.25-2.25 5-2.25c-1.25 2.25-3 4.15-5 5.4c-2-1.25-3.75-3.15-5-5.4Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.v0rzdcctt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.25 3.75l5.5 3.5h6.5l5.5-3.5V9.5c0 3.5-4.75 8.75-8.75 11c-4-2.25-8.75-7.5-8.75-11Z");
}

.vt-vgvh_a {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 10.25h.01m6.49 0h.01");
}

</style>
