<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pbbm_cbbc"/><path class="uw6x37bpc"/><path class="x2r2-hbds"/><path class="ygnemt3bx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:hobby-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pbbm_cbbc {
  fill: currentColor;
  d: path("M12 20c-4 -3 -9 -7 -7 -11.5 1.5 -3 5 -2 7 1 2 -3 5.5 -4 7 -1C21 13 16 17 12 20");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.uw6x37bpc {
  d: path("M12 20c-4 -3 -9 -7 -7 -11.5 1.5 -3 5 -2 7 1 2 -3 5.5 -4 7 -1C21 13 16 17 12 20");
}

.x2r2-hbds {
  d: path("m8 4 2 -2");
}

.ygnemt3bx {
  d: path("m16 4 -2 -2");
}

</style>
