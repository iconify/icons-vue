<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><radialGradient id="SVGwZwAicDR" cx="50.141%" cy="50.003%" r="50.119%" fx="50.141%" fy="50.003%"><stop offset="0%" class="p9rps_sqh"/><stop offset="100%" class="e28e5w85u"/></radialGradient></defs><circle class="zzkut7b9o"/><circle class="ndwfw61fw"/><circle class="ywh-yvegr"/><circle class="hbjvl2ykn"/><circle class="gxe_-hbuq"/><circle class="km_0uzb8q"/><circle class="ywtzk3sfv"/><circle class="d8kbqib5h"/><circle fill="url(#SVGwZwAicDR)" class="wa9063b4i"/><circle class="vroha88fh"/><path class="xxp3nta2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:browserstack" /></template>
<style>
.d8kbqib5h {
  cx: 137.069px;
  cy: 97.376px;
  r: 52.506px;
  fill: var(--svg-color--02b2d6, #02b2d6);
}

.e28e5w85u {
  stop-color: var(--svg-color--4c4c4c, #4c4c4c);
}

.gxe_-hbuq {
  cx: 131.542px;
  cy: 115.062px;
  r: 84.839px;
  fill: var(--svg-color--6db64c, #6db64c);
}

.hbjvl2ykn {
  cx: 138.174px;
  cy: 108.43px;
  r: 91.471px;
  fill: var(--svg-color--bfd141, #bfd141);
}

.km_0uzb8q {
  cx: 118.001px;
  cy: 101.798px;
  r: 71.298px;
  fill: var(--svg-color--afdbe7, #afdbe7);
}

.ndwfw61fw {
  cx: 114.961px;
  cy: 115.615px;
  r: 114.685px;
  fill: var(--svg-color--e86f32, #e86f32);
}

.p9rps_sqh {
  stop-color: var(--svg-color--797979, #797979);
}

.vroha88fh {
  cx: 129.331px;
  cy: 104.837px;
  r: 44.768px;
  fill: var(--svg-color--231f20, #231f20);
}

.wa9063b4i {
  cx: 129.331px;
  cy: 104.837px;
  r: 44.768px;
}

.xxp3nta2n {
  fill: var(--svg-color--fff, #fff);
  d: path("M141.088 98.971c4.439 1.992 10.56-2.016 13.672-8.951s2.036-14.173-2.402-16.164c-4.44-1.992-10.56 2.016-13.672 8.951s-2.037 14.173 2.402 16.164");
}

.ywh-yvegr {
  cx: 130.16px;
  cy: 100.416px;
  r: 99.485px;
  fill: var(--svg-color--e53d42, #e53d42);
}

.ywtzk3sfv {
  cx: 129.607px;
  cy: 89.915px;
  r: 59.691px;
  fill: var(--svg-color--57badf, #57badf);
}

.zzkut7b9o {
  cx: 127.949px;
  cy: 128.603px;
  r: 127.397px;
  fill: var(--svg-color--f5bb60, #f5bb60);
}

</style>
