<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qht_xwbpv"/><path class="ey50rob7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bottle-bag" /></template>
<style>
.ey50rob7l {
  d: path("M8.25 12.5H9.5A1.5 1.5 0 0 1 11 14v1.5A1.5 1.5 0 0 1 9.5 17H8.25a1.5 1.5 0 0 1-1.5-1.5V14a1.5 1.5 0 0 1 1.5-1.5m9.75 5c-1.5-2.25-3.75-2.25-3.75-.75s2.25 2 3.75.75m0 0c1.5-2.25 3.75-2.25 3.75-.75s-2.25 2-3.75.75m-.75 1.75l-.5 2.25m2-2.25l.5 2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qht_xwbpv {
  d: path("M14.001 21.414q-.243.086-.501.086h-7q-.074 0-.147-.007t-.146-.022t-.142-.036q-.071-.021-.139-.049t-.133-.063t-.126-.076t-.119-.087q-.057-.047-.109-.099t-.099-.109q-.046-.057-.087-.119t-.076-.126q-.035-.065-.063-.133t-.049-.139q-.022-.07-.036-.142q-.015-.073-.022-.146T5 20v-8.5C5 9.5 5.5 8 8 7V2.5h4V7c2.5 1 3 2.5 3 4.5v1.44");
}

</style>
