<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qp28wyb6u"/><path class="t_je4wbme"/><circle class="hk4_ptb-x"/><path class="h16qlybxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:id-scan-sharp" /></template>
<style>
.h16qlybxm {
  d: path("M15.75 17.5L17 18.75l2.25-2.5");
}

.hk4_ptb-x {
  cx: 17.5px;
  cy: 17.5px;
  r: 3.75px;
}

.qp28wyb6u {
  d: path("M2.75 3.75h18.5v13.5H2.75z");
}

.t_je4wbme {
  d: path("M10 8.5a2 2 0 1 1-4 0a2 2 0 1 1 4 0M5.5 14l.714-2h3.572l.714 2M13 8h4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
