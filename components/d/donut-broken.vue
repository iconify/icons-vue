<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="gp0egaclj"/><path class="a0u0egbsz"/><path class="soo7ncb-d"/><path class="s0qi5sbmn"/><path class="q1801mj_c"/><path class="v92prbclx"/><path class="e-hxpcc7k"/><path class="to56nbbry"/><path class="cn1xlvb1s"/><path class="a0k0xfo0n"/><path class="rqpfqtv9c"/><path class="xdbgpgb8u"/><path class="kir6y30_z"/><path class="ssti_6bzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:donut-broken" /></template>
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

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kir6y30_z {
  d: path("M2.05371 13.0422C2.05371 13.0422 4.20098 15.0002 6.00012 15.0002C7.21212 15.0002 8.62062 14.0928 9.4016 13.5004");
}

.q1801mj_c {
  d: path("M10.5 7L9.13397 7.36603");
}

.rqpfqtv9c {
  d: path("M3.68293 10.3497L3.60427 8.93769");
}

.s0qi5sbmn {
  d: path("M12 5L11 4");
}

.soo7ncb-d {
  d: path("M19 7L20 6");
}

.ssti_6bzn {
  d: path("M14.0073 14.2295C14.4786 14.6448 15.0873 15 15.8052 15C17.4946 15 17.4946 13 19.1841 13C20.2616 13 21.1101 13.8136 21.5833 14.4029L21.6795 14.5209");
}

.to56nbbry {
  d: path("M7 5L6 4");
}

.v92prbclx {
  d: path("M16.6497 8.97651L16.7161 10.3892");
}

.xdbgpgb8u {
  d: path("M7 20.6622C8.47087 21.513 10.1786 22 12 22C17.5228 22 22 17.5228 22 12C22 6.47715 17.5228 2 12 2C6.47715 2 2 6.47715 2 12C2 13.8214 2.48697 15.5291 3.33782 17");
}

</style>
