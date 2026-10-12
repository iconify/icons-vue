<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="apqag2bvo"/><path class="dpwr--7jr"/><path class="k-oiw3ayt"/><rect class="n6-4xacwx"/><circle class="biq2jjb5i"/><path class="tb6q2fbtf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cd-drive" /></template>
<style>
.apqag2bvo {
  width: 18.5px;
  height: 5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.biq2jjb5i {
  cx: 12px;
  cy: 15.75px;
  r: 3px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.dpwr--7jr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 5.25h6");
}

.k-oiw3ayt {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 5.25h.01");
}

.n6-4xacwx {
  width: 14.5px;
  height: 11px;
  x: 4.75px;
  y: 10.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.tb6q2fbtf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 15.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
