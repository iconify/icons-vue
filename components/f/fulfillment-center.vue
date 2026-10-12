<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r2x3_w_0k"/><rect class="j7-uhil1e"/><path class="xmgz99k_i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fulfillment-center" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j7-uhil1e {
  width: 7px;
  height: 7.5px;
  x: 8.5px;
  y: 13.75px;
  rx: 0.75px;
}

.r2x3_w_0k {
  d: path("M2.75 21.25V9.4a1 1 0 0 1 .48-.85l4.5-2.7a.5.5 0 0 1 .77.43V9l4.73-2.84a.5.5 0 0 1 .77.43V9l4.73-2.84a.5.5 0 0 1 .77.43v14.66Z");
}

.xmgz99k_i {
  d: path("M12 13.75v2.5");
}

</style>
