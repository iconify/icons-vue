<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cpc3z_b1u"/><path class="mz3hiybxq"/><path class="b3_fr3bsp"/><path class="kdmnrabtq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gradient-descent-duotone-thin" /></template>
<style>
.b3_fr3bsp {
  d: path("M3 3h6v6h6v6h6");
}

.cpc3z_b1u {
  fill: currentColor;
  d: path("M17 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kdmnrabtq {
  d: path("M17 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.mz3hiybxq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 3h6v6h6v6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
