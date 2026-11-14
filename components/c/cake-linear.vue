<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qk1ykkkcf"/><path class="yjli4ujqg"/><path class="vm5pbzb0y"/><path class="qih925b2y"/><path class="tcl6hjbbl"/><path class="cunofwb0r"/><path class="utr0h8b_n"/><path class="xln7a9flp"/><path class="sv3tz1bib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cake-linear" /></template>
<style>
.cunofwb0r {
  d: path("M16 10V6.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qih925b2y {
  d: path("M8 10V6.25");
}

.qk1ykkkcf {
  d: path("M22 21.5H2");
}

.sv3tz1bib {
  d: path("M16 2.5H16.0001");
}

.tcl6hjbbl {
  d: path("M12 10V6.25");
}

.utr0h8b_n {
  d: path("M8 2.5H8.0001");
}

.vm5pbzb0y {
  d: path("M4 15.5C5.2 17.1 7.2 17.1 8 15.7C8.9 14.1 11.1 14.1 12 15.7C12.9 17.1 15.1 17.1 16 15.7C16.8 14.1 18.8 14.1 20 15.5");
}

.xln7a9flp {
  d: path("M12 2.5H12.0001");
}

.yjli4ujqg {
  d: path("M4 21.5V14C4 12.1144 4 11.1716 4.5858 10.5858C5.1716 10 6.1144 10 8 10H16C17.8856 10 18.8284 10 19.4142 10.5858C20 11.1716 20 12.1144 20 14V21.5");
}

</style>
