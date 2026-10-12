<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ivt5uminb"/><path class="iv58s7f2b"/><path class="nxk4t6bot"/><path class="bgpwvwb-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:altar-table-sharp" /></template>
<style>
.bgpwvwb-w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 14.5h16.5M9 21.25V17h6v4.25");
}

.iv58s7f2b {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 6.25h.01m11.99 0h.01");
}

.ivt5uminb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75v7M9.75 5h4.5M6 11.75V8.5m12 3.25V8.5");
}

.nxk4t6bot {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 11.75h16.5v9.5H3.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
