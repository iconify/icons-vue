<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><radialGradient id="SVGsr9J0dXk" cx="290.179" cy="-321.728" r="8.902" gradientTransform="matrix(1.711 .138 .094 -1.169 -444.134 -394.022)" gradientUnits="userSpaceOnUse"><stop offset="0" class="h-u97vs8u"/><stop offset="1" class="lkf9wobch"/></radialGradient><linearGradient id="SVGr38c3Wdn" x1="262.559" x2="262.559" y1="-662.427" y2="-659.102" gradientTransform="matrix(1 0 0 -1 -250.518 -647.956)" gradientUnits="userSpaceOnUse"><stop offset="0" class="i1x2zac2t"/><stop offset="1" class="ymr_cqbuq"/></linearGradient></defs><path class="wmy0s9hki"/><path class="q1imd7ygz"/><rect class="qttgjlbdi"/><rect fill="url(#SVGsr9J0dXk)" class="c_vl693jx"/><rect class="a53u8zbsm"/><path class="y5gg7c-jf"/><path class="cl_6_b0qt"/><path class="vy1e-mbhu"/><path fill="url(#SVGr38c3Wdn)" class="cw9gyobdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-nuget-opened" /></template>
<style>
.a53u8zbsm {
  width: 14.57px;
  height: 14.57px;
  x: 14.528px;
  y: 15.138px;
  fill: var(--svg-color--016fd2, #016fd2);
  rx: 4.565px;
  ry: 4.565px;
}

.c_vl693jx {
  width: 17.092px;
  height: 16.917px;
  x: 13.558px;
  y: 13.713px;
  opacity: var(--svg-opacity--0-823, 0.823);
  rx: 5.47px;
  ry: 5.47px;
}

.cl_6_b0qt {
  fill: var(--svg-color--fff, #fff);
  d: path("M28.375 25.2a3.733 3.733 0 1 1-7.467 0a3.733 3.733 0 1 1 7.467 0m-8.458-6.821a2.158 2.158 0 0 1-4.317 0a2.158 2.158 0 0 1 4.317 0");
}

.cw9gyobdm {
  d: path("M13.617 12.663a1.575 1.575 0 0 1-3.15 0a1.575 1.575 0 0 1 3.15 0");
}

.h-u97vs8u {
  stop-color: var(--svg-color--0663b4, #0663b4);
}

.i1x2zac2t {
  stop-color: var(--svg-color--047fc7, #047fc7);
}

.lkf9wobch {
  stop-color: var(--svg-color--16adff, #16adff);
  stop-opacity: 0.685;
}

.q1imd7ygz {
  fill: var(--svg-color--7baddb, #7baddb);
  d: path("M25.7 13.7H.5l3.8 12.8h25.2z");
}

.qttgjlbdi {
  width: 17.792px;
  height: 17.792px;
  x: 13.208px;
  y: 13.188px;
  fill: var(--svg-color--c7ebf1, #c7ebf1);
  rx: 5.775px;
  ry: 5.775px;
}

.vy1e-mbhu {
  fill: var(--svg-color--cbedf2, #cbedf2);
  fill-opacity: var(--svg-fill-opacity--0-925, 0.925);
  d: path("M14.083 12.663a2.042 2.042 0 1 1-4.083 0a2.042 2.042 0 1 1 4.083 0");
}

.wmy0s9hki {
  fill: var(--svg-color--7baddb, #7baddb);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Z");
}

.y5gg7c-jf {
  fill: var(--svg-color--5fffe6, #5fffe6);
  d: path("M30.629 18.763a5.467 5.467 0 0 0-5.449-5.051h-6.151a5.47 5.47 0 0 0-5.47 5.47v5.976c0 .124.01.245.018.367q.586.032 1.181.032a21.9 21.9 0 0 0 15.871-6.794");
  opacity: var(--svg-opacity--0-173, 0.173);
}

.ymr_cqbuq {
  stop-color: var(--svg-color--11abe8, #11abe8);
}

</style>
