<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="jf3edpbej"/><path class="kpoaq_qvj"/><rect class="ptmr3obkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:field-monitor" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jf3edpbej {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 3.25px;
  rx: 2px;
}

.kpoaq_qvj {
  d: path("M6.5 8V7h1m10 1V7h-1m-10 4v1h1m10-1v1h-1M12 15.75v2.5");
}

.ptmr3obkw {
  width: 7.5px;
  height: 3px;
  x: 8.25px;
  y: 18.25px;
  rx: 1.25px;
}

</style>
