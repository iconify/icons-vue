<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="eq_0xmbwt"/><path class="oz7xebbvk"/><rect class="bre6c3u2t"/><path class="cufhi39km"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ev-charger" /></template>
<style>
.bre6c3u2t {
  width: 4px;
  height: 4px;
  x: 15.25px;
  y: 16.75px;
  rx: 1px;
}

.cufhi39km {
  d: path("M19.25 18h2m-2 1.5h2");
}

.eq_0xmbwt {
  width: 11px;
  height: 13px;
  x: 3.25px;
  y: 2.75px;
  rx: 3px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oz7xebbvk {
  d: path("m10.5 5l-3 4.25h3.75l-3 4.25m.5 2.25v.5a2.5 2.5 0 0 0 2.5 2.5h4");
}

</style>
