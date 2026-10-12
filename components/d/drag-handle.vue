<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="uva_accpf"/><circle class="o2ojnnbap"/><circle class="oy91ely1a"/><circle class="muwu9uvyd"/><circle class="joyo2ddzr"/><circle class="r27_c8b6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drag-handle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.joyo2ddzr {
  cx: 9px;
  cy: 18.5px;
  r: 1.25px;
}

.muwu9uvyd {
  cx: 15px;
  cy: 12px;
  r: 1.25px;
}

.o2ojnnbap {
  cx: 15px;
  cy: 5.5px;
  r: 1.25px;
}

.oy91ely1a {
  cx: 9px;
  cy: 12px;
  r: 1.25px;
}

.r27_c8b6j {
  cx: 15px;
  cy: 18.5px;
  r: 1.25px;
}

.uva_accpf {
  cx: 9px;
  cy: 5.5px;
  r: 1.25px;
}

</style>
