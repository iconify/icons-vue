<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xogjh4bhh"/><path class="taauto6yu"/><circle class="shu3xdl9q"/><circle class="gp0egaclj"/><path class="a0u0egbsz"/><path class="gq6_obb9a"/><path class="s0qi5sbmn"/><path class="txyb0r8kh"/><path class="ppbot7hht"/><path class="e-hxpcc7k"/><path class="kocz27bxb"/><path class="cn1xlvb1s"/><path class="a0k0xfo0n"/><path class="i-ok3bfpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:donut-line-duotone" /></template>
<style>
.a0k0xfo0n {
  d: path("M5.66477 12.6414L6.5 11.5002");
}

.a0u0egbsz {
  d: path("M14.5 7L16 5");
}

.cn1xlvb1s {
  d: path("M6.79245 9.14385L6.20722 7.85641");
}

.e-hxpcc7k {
  d: path("M20.6777 10.085L18.9996 11.5629");
}

.gp0egaclj {
  cx: 12px;
  cy: 12px;
  r: 3px;
}

.gq6_obb9a {
  d: path("M19 7L20 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.i-ok3bfpn {
  d: path("M3.68293 10.3497L3.60427 8.93769");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kocz27bxb {
  d: path("M7 5L6 4");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ppbot7hht {
  d: path("M16.6497 8.97651L16.7161 10.3892");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.s0qi5sbmn {
  d: path("M12 5L11 4");
}

.shu3xdl9q {
  cx: 12px;
  cy: 12px;
  r: 10px;
}

.taauto6yu {
  d: path("M14.0073 14.2295C14.4786 14.6448 15.0873 15 15.8052 15C17.4946 15 17.4946 13 19.1841 13C20.2616 13 21.1101 13.8136 21.5833 14.4029L21.6795 14.5209");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.txyb0r8kh {
  d: path("M10.5 7L9.13397 7.36603");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xogjh4bhh {
  d: path("M2.05371 13.0422C2.05371 13.0422 4.20098 15.0002 6.00012 15.0002C7.21212 15.0002 8.62062 14.0928 9.4016 13.5004");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
