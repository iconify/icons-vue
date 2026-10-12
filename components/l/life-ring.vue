<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i_7fi_bhg"/><circle class="u4_6jmbkl"/><path class="o5o-njbiu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:life-ring" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i_7fi_bhg {
  d: path("M7.75 2.75h8.5m-4.25 0v3.5");
}

.o5o-njbiu {
  d: path("M12 10.5a3.25 3.25 0 1 0 0 6.5a3.25 3.25 0 1 0 0-6.5m-2.87 1.73l-3.76-1.98m5.11.63L8.5 7.12m5.02 3.76l1.98-3.76m-.63 5.11l3.76-1.98m-3.76 5.02l3.76 1.98m-5.11-.63l1.98 3.76m-5.02-3.76L8.5 20.38m.63-5.11l-3.76 1.98");
}

.u4_6jmbkl {
  cx: 12px;
  cy: 13.75px;
  r: 7.5px;
}

</style>
