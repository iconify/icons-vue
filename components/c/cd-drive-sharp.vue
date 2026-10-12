<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="dg72oebpl"/><path class="k-oiw3ayt"/><path class="g59mvcbji"/><circle class="biq2jjb5i"/><path class="tb6q2fbtf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cd-drive-sharp" /></template>
<style>
.biq2jjb5i {
  cx: 12px;
  cy: 15.75px;
  r: 3px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.dg72oebpl {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v5H2.75zm3.5 2.5h6");
}

.g59mvcbji {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 10.25h14.5v11H4.75z");
}

.k-oiw3ayt {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 5.25h.01");
}

.tb6q2fbtf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 15.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
