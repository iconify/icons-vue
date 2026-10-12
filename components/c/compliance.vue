<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zx3l9v_bo"/><path class="inenlrlfi"/><circle class="o2mgrpbno"/><path class="sjcx_2czi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:compliance" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.inenlrlfi {
  d: path("M13.75 2.75v3.5a2 2 0 0 0 2 2h3.5m-11 3.5h3.5M8.25 15h2");
}

.o2mgrpbno {
  cx: 16.5px;
  cy: 15.25px;
  r: 3.25px;
}

.sjcx_2czi {
  d: path("M14.75 18v3.25L16.5 20l1.75 1.25V18");
}

.zx3l9v_bo {
  d: path("M11.5 21.25H7.25a2.5 2.5 0 0 1-2.5-2.5V5.25a2.5 2.5 0 0 1 2.5-2.5h6.5l5.5 5.5v2");
}

</style>
