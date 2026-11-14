<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="amap8u1lr"/><path class="vtmibdvzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:concrete-cube-test" /></template>
<style>
.amap8u1lr {
  d: path("M3 4h18M3 20h18M12.765 4.453l5.25 3.111a1.5 1.5 0 0 1 .735 1.291v6.29a1.5 1.5 0 0 1-.735 1.291l-5.25 3.111a1.5 1.5 0 0 1-1.53 0l-5.25-3.111a1.5 1.5 0 0 1-.735-1.291v-6.29a1.5 1.5 0 0 1 .735-1.291l5.25-3.111a1.5 1.5 0 0 1 1.53 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vtmibdvzj {
  d: path("M5.25 8L12 12l6.75-4M12 12v8");
}

</style>
