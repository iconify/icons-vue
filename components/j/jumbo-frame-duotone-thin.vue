<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ddf9nt86r"/><path class="oh4p-ccfe"/><path class="vh0_rdbqi"/><path class="t8z7o_gvd"/><path class="aalbzcb_j"/><path class="vslz5yb3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:jumbo-frame-duotone-thin" /></template>
<style>
.aalbzcb_j {
  d: path("M2 5.5h20");
}

.ddf9nt86r {
  fill: currentColor;
  d: path("M2 10a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oh4p-ccfe {
  d: path("M2 10a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.t8z7o_gvd {
  d: path("M22 4v3");
}

.vh0_rdbqi {
  d: path("M2 4v3");
}

.vslz5yb3q {
  d: path("M6 12h12");
}

</style>
