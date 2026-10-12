<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="dx_kjj12y"/><path class="zx5-43bsd"/><path class="ywhqqkbci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:khussa-sharp" /></template>
<style>
.dx_kjj12y {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9.75c0 2 1.25 3.25 3.25 3s3-1.25 4.5-3.25h10v8H8.5C4.75 17.5 3 14.75 3 9.75Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.ywhqqkbci {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.25 14.5h.01m2.49 0h.01");
}

.zx5-43bsd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 15h3.643l2.357-2.75");
}

</style>
