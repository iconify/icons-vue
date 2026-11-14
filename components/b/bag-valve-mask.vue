<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rg8xsb7ai"/><path class="v_mmj0bvv"/><path class="rkam_bcov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bag-valve-mask" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rg8xsb7ai {
  d: path("M8 21.5v-4c-2.5-1.75-3.5-4.25-3.5-7c0-3.288 1.945-5.977 4.793-7.026M15 20.926v.574");
}

.rkam_bcov {
  d: path("M12 4.5a4.75 2.25 0 1 0 9.5 0a4.75 2.25 0 1 0-9.5 0m7 2.25v2.5");
}

.v_mmj0bvv {
  fill: currentColor;
  d: path("M16.5 9.5c3.5-.5 5.25 2 5.25 4.5c0 2.75-2 4.5-5 4.75c-1-3-1-6.25-.25-9.25");
}

</style>
