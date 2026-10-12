<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q98j_ebpe"/><rect class="c5skzxr6h"/><path class="lucsi4bcy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jackhammer" /></template>
<style>
.c5skzxr6h {
  width: 6.5px;
  height: 7.5px;
  x: 8.75px;
  y: 7.5px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lucsi4bcy {
  d: path("M8.75 10.5h6.5M12 15v5.5m-6-1l-2 1.75m14-1.75l2 1.75m-13.5-4.5H4m13.5 0H20");
}

.q98j_ebpe {
  d: path("M2.75 4.5h18.5M12 4.5v3");
}

</style>
