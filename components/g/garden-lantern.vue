<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wnt8spd4r"/><path class="xhob0wh_s"/><path class="bolzvyb2z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:garden-lantern" /></template>
<style>
.bolzvyb2z {
  d: path("M9.427 18.5h5.146a1.5 1.5 0 0 1 1.342.829L16 19.5a.69.69 0 0 1-.618 1H8.618a.69.69 0 0 1-.618-1l.085-.171a1.5 1.5 0 0 1 1.342-.829M12 15.75c-2 0-2.25-2 0-4.5c2.25 2.5 2 4.5 0 4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wnt8spd4r {
  d: path("M10.5 5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.xhob0wh_s {
  d: path("M9.526 6.5h4.948a1.5 1.5 0 0 1 .937.329l.839.671a.562.562 0 0 1-.351 1H8.101a.562.562 0 0 1-.351-1l.839-.671a1.5 1.5 0 0 1 .937-.329m-.276 2h5.5a1.75 1.75 0 0 1 1.75 1.75v6.5a1.75 1.75 0 0 1-1.75 1.75h-5.5a1.75 1.75 0 0 1-1.75-1.75v-6.5A1.75 1.75 0 0 1 9.25 8.5");
}

</style>
