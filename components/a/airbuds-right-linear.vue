<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="idppisblu"/><path class="ow-__pceu"/><circle class="b0rut8bma"/><path class="txolo1bem"/><path class="rivq1nv_i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:airbuds-right-linear" /></template>
<style>
.b0rut8bma {
  cx: 7.5px;
  cy: 16.5px;
  r: 5.5px;
}

.idppisblu {
  d: path("M16 18.6667V12C16 11.4477 15.5523 11 15 11C13.3431 11 12 9.65685 12 8V5.375L12 5.33562C12.0095 3.49738 13.4974 2.00954 15.3356 2.00004L15.375 2L15.4406 2.00007C18.5044 2.01591 20.9841 4.49563 20.9999 7.55936L21 7.625V18.6667M16 18.6667V19.5C16 19.6393 16 19.7089 16.003 19.7678C16.0634 20.973 17.027 21.9366 18.2322 21.997C18.2911 22 18.3607 22 18.5 22C18.6393 22 18.7089 22 18.7678 21.997C19.973 21.9366 20.9366 20.973 20.997 19.7678C21 19.7089 21 19.6393 21 19.5V18.6667M16 18.6667H21");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ow-__pceu {
  d: path("M15 5V8");
}

.rivq1nv_i {
  stroke-linejoin: round;
  d: path("M6 19V14H7.5C8.32843 14 9 14.5596 9 15.25C9 15.9404 8.32843 16.5 7.5 16.5M6 14V16.5H7.5M7.5 16.5L9 19");
}

.txolo1bem {
  d: path("M9.00008 5.10001C7.04095 5.49769 5.49778 7.04086 5.1001 8.99999");
}

</style>
