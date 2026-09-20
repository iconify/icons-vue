<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="q1m2erv2p"/><ellipse class="rgbz0pbov"/><ellipse class="dgfjje3vu"/><path class="fqffn_j5l"/><path class="g3vplobpv"/><path class="q2j_zgflt"/><path class="f7-mgcc5j"/><path class="uzmuao30n"/><path class="cjw_z_lnf"/><path class="p47d874hy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:face-with-thermometer" /></template>
<style>
.cjw_z_lnf {
  fill: var(--svg-color--67757f, #67757f);
  d: path("m18.599 25.228l1.234 1.598l.741-.595l-1.197-1.587zm2.223-1.661l1.235 1.598l.741-.595l-1.197-1.587zm2.184-1.619l1.234 1.598l.741-.595l-1.197-1.587zm2.181-1.66l1.235 1.597l.741-.594l-1.197-1.587zm2.238-1.641l1.235 1.598l.74-.595l-1.196-1.587zm2.14-1.618l1.235 1.598l.74-.595l-1.196-1.587z");
}

.dgfjje3vu {
  cx: 23.5px;
  cy: 16.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

.f7-mgcc5j {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M35.474 15.729a2.5 2.5 0 0 0-3.501-.5L14.767 28.137c.646-.242 1.51-.444 2.615-.522c.256-.018 2.66-.627 2.66-.627l1.293 1.036s.911.367 1.197.539l12.444-9.335a2.5 2.5 0 0 0 .498-3.499");
}

.fqffn_j5l {
  fill: var(--svg-color--664500, #664500);
  d: path("M29 12c-5.554 0-7.802-4.367-7.895-4.553a1 1 0 0 1 1.787-.899C22.967 6.694 24.713 10 29 10a1 1 0 1 1 0 2m-22-.006a1 1 0 0 1 0-2c5.083 0 5.996-3.12 6.033-3.253c.145-.528.69-.848 1.219-.709s.851.673.718 1.205c-.049.194-1.266 4.757-7.97 4.757");
}

.g3vplobpv {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("m35.968 17.068l-4.005.813l-16.187 10.508l7.118.963l11.685-7.211c.703-.431.994-.835 1.198-1.747s.191-3.326.191-3.326");
}

.p47d874hy {
  fill: var(--svg-color--452e04, #452e04);
  d: path("m22.531 28.563l.805.522s-.197-.362-.526-.726z");
}

.q1m2erv2p {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.q2j_zgflt {
  fill: var(--svg-color--664500, #664500);
  d: path("M23.485 29.379C23.474 29.335 22.34 26.5 18 26.5s-5.474 2.835-5.485 2.879a.5.5 0 0 0 .232.544a.51.51 0 0 0 .596-.06C13.352 29.855 14.356 29 18 29c3.59 0 4.617.83 4.656.863a.5.5 0 0 0 .829-.484");
}

.rgbz0pbov {
  cx: 12.5px;
  cy: 16.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

.uzmuao30n {
  fill: var(--svg-color--da2f47, #da2f47);
  d: path("M28.686 20.87c-.448-.596-.787-1.145-1.383-.698l-9.922 7.443c.256-.018.5-.042.783-.044c1.36-.009 2.4.195 3.17.452l7.588-5.692c.596-.447.211-.864-.236-1.461");
}

</style>
