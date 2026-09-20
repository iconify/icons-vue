<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGXXeOvc8f" x1="-231.439" x2="-231.456" y1="265.977" y2="265.902" gradientTransform="matrix(161.096 0 0 -241.217 37302.352 64171.913)" gradientUnits="userSpaceOnUse"><stop offset="0" class="sezoddb5r"/><stop offset="1" class="te6563h5y"/></linearGradient><linearGradient id="SVG1JBYRSIF" x1="-231.867" x2="-231.873" y1="265.942" y2="265.94" gradientTransform="matrix(224.69 0 0 -241.214 52119.718 64171.207)" gradientUnits="userSpaceOnUse"><stop offset="0" class="p_qts-b_r"/><stop offset=".071" class="a2gzbfbcc"/><stop offset=".321" class="tipw_dbaw"/><stop offset=".623" class="ws0rd4b2v"/><stop offset="1" class="k05n1gbkm"/></linearGradient><linearGradient id="SVGF2D5Qq2K" x1="-232.001" x2="-231.981" y1="265.98" y2="265.905" gradientTransform="matrix(169.755 0 0 -241.217 39406.126 64171.912)" gradientUnits="userSpaceOnUse"><stop offset="0" class="l3_3-ephw"/><stop offset="1" class="ms0tavq2o"/></linearGradient></defs><path class="y97k7rbnj"/><path fill="url(#SVGXXeOvc8f)" class="mi74ydbgf"/><path class="ljbffchaw"/><path fill="url(#SVG1JBYRSIF)" class="x2ws0ab8m"/><path fill="url(#SVGF2D5Qq2K)" class="rkppjubdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-azure-opened" /></template>
<style>
.a2gzbfbcc {
  stop-opacity: 0.2;
}

.k05n1gbkm {
  stop-opacity: 0;
}

.l3_3-ephw {
  stop-color: var(--svg-color--3ccbf4, #3ccbf4);
}

.ljbffchaw {
  fill: var(--svg-color--0078d4, #0078d4);
  d: path("M26.26 24.5h-9.4a.435.435 0 0 0-.3.753l6.04 5.637a.95.95 0 0 0 .648.255h5.322Z");
}

.mi74ydbgf {
  d: path("M17.646 12.272h5.928L17.421 30.5a.945.945 0 0 1-.9.643h-4.609a.944.944 0 0 1-.894-1.245l5.733-16.986a.945.945 0 0 1 .9-.643Z");
}

.ms0tavq2o {
  stop-color: var(--svg-color--2892df, #2892df);
}

.p_qts-b_r {
  stop-opacity: 0.3;
}

.rkppjubdx {
  d: path("M25.217 12.914a.94.94 0 0 0-.894-.642h-6.606a.94.94 0 0 1 .894.642L24.344 29.9a.944.944 0 0 1-.894 1.246h6.606a.944.944 0 0 0 .894-1.246Z");
}

.sezoddb5r {
  stop-color: var(--svg-color--114a8b, #114a8b);
}

.te6563h5y {
  stop-color: var(--svg-color--0669bc, #0669bc);
}

.tipw_dbaw {
  stop-opacity: 0.1;
}

.ws0rd4b2v {
  stop-opacity: 0.05;
}

.x2ws0ab8m {
  d: path("M17.646 12.272a.94.94 0 0 0-.9.655l-5.721 16.959a.942.942 0 0 0 .89 1.261h4.732a1.01 1.01 0 0 0 .776-.66l1.141-3.364l4.077 3.8a.97.97 0 0 0 .607.221h5.3L26.226 24.5h-6.78L23.6 12.272Z");
}

.y97k7rbnj {
  fill: var(--svg-color--7db4d3, #7db4d3);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21Zm-7.2 2.1h7.1v2.1h-8.1Zm5.5 6.1H6.6v-1.9h20.8v7.626Z");
}

</style>
