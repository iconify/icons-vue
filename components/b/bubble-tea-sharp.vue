<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="x_09jd0qt"/><path class="od_c_acvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bubble-tea-sharp" /></template>
<style>
.od_c_acvu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 18h.01m4.49 0h.01M12 14.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.x_09jd0qt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 7.25h14.5l-1.5 12.5l-.219 1.516L16 21.25H8l-1.531.016l-.219-1.516Zm8.75 0l2-4.5H18");
}

</style>
