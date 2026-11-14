<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l087an1gy"/><path class="eo1zoob1l"/><path class="kb42vqxcy"/><path class="bzkft-vxe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:change-of-address" /></template>
<style>
.bzkft-vxe {
  d: path("M18.75 14.25L20.5 16l-1.75 1.75");
}

.eo1zoob1l {
  d: path("M5 9v11q0 .098.019.195t.057.188t.093.173q.054.081.124.151t.151.124q.082.055.173.093t.188.057T6 21h6.186m5.6 0H18q.125 0 .246-.031q.121-.03.231-.09t.201-.144q.092-.085.16-.19M19 11.428V9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kb42vqxcy {
  d: path("M8.5 21v-5H12v5m3 .5c0-3.5 2-5.5 5.5-5.5");
}

.l087an1gy {
  d: path("M2.5 11L12 3l9.5 8");
}

</style>
