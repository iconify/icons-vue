<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ls2to96st"/><path class="sa-r0267g"/><path class="xikv_u7kv"/><path class="j0wt0360j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:column-group" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j0wt0360j {
  d: path("M13.5 13.5V20a1.5 1.5 0 0 0 1.5 1.5h4a1.5 1.5 0 0 0 1.5-1.5v-6.5M3.5 17h7m3 0h7m-17-9V6h6m5 0h6v2m-9.25-4.5h1.5a1.75 1.75 0 0 1 1.75 1.75v1.5a1.75 1.75 0 0 1-1.75 1.75h-1.5A1.75 1.75 0 0 1 9.5 6.75v-1.5a1.75 1.75 0 0 1 1.75-1.75m-.5 2.5h2.5");
}

.ls2to96st {
  fill: currentColor;
  d: path("M3.5 13.5V12A1.5 1.5 0 0 1 5 10.5h4a1.5 1.5 0 0 1 1.5 1.5v1.5Z");
}

.sa-r0267g {
  d: path("M3.5 13.5V20A1.5 1.5 0 0 0 5 21.5h4a1.5 1.5 0 0 0 1.5-1.5v-6.5");
}

.xikv_u7kv {
  fill: currentColor;
  d: path("M13.5 13.5V12a1.5 1.5 0 0 1 1.5-1.5h4a1.5 1.5 0 0 1 1.5 1.5v1.5Z");
}

</style>
