<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="cysmaobde"/><path class="e5ntul8dj"/><rect class="dsijizygp"/><path class="bdqcikbdi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chainsaw" /></template>
<style>
.bdqcikbdi {
  d: path("M14 12.6h4.75m-13.5.9h3.5");
}

.cysmaobde {
  width: 8.5px;
  height: 9px;
  x: 2.75px;
  y: 8px;
  rx: 2px;
}

.dsijizygp {
  width: 9.75px;
  height: 4.75px;
  x: 11.5px;
  y: 10.25px;
  rx: 2.25px;
}

.e5ntul8dj {
  d: path("M4.75 8V6.25a1.5 1.5 0 0 1 1.5-1.5h2.5a1.5 1.5 0 0 1 1.5 1.5V8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
