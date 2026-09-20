<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGMZsxHetM" x1="-231.477" x2="-231.5" y1="266.014" y2="265.909" gradientTransform="matrix(161.096 0 0 -241.217 37302.352 64171.913)" gradientUnits="userSpaceOnUse"><stop offset="0" class="sezoddb5r"/><stop offset="1" class="te6563h5y"/></linearGradient><linearGradient id="SVGGSAnlyQy" x1="-231.889" x2="-231.896" y1="265.964" y2="265.962" gradientTransform="matrix(224.69 0 0 -241.214 52119.718 64171.207)" gradientUnits="userSpaceOnUse"><stop offset="0" class="p_qts-b_r"/><stop offset=".071" class="a2gzbfbcc"/><stop offset=".321" class="tipw_dbaw"/><stop offset=".623" class="ws0rd4b2v"/><stop offset="1" class="k05n1gbkm"/></linearGradient><linearGradient id="SVGPeNBWbch" x1="-232.026" x2="-231.998" y1="266.018" y2="265.914" gradientTransform="matrix(169.755 0 0 -241.217 39406.126 64171.912)" gradientUnits="userSpaceOnUse"><stop offset="0" class="l3_3-ephw"/><stop offset="1" class="ms0tavq2o"/></linearGradient></defs><path fill="url(#SVGMZsxHetM)" class="djcdmcbnm"/><path class="tugb-hb9z"/><path fill="url(#SVGGSAnlyQy)" class="vitvmyb3q"/><path fill="url(#SVGPeNBWbch)" class="imt_tccjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-azure" /></template>
<style>
.a2gzbfbcc {
  stop-opacity: 0.2;
}

.djcdmcbnm {
  d: path("M11.343 2.834h8.27l-8.585 25.435a1.32 1.32 0 0 1-1.249.9H3.343a1.316 1.316 0 0 1-1.243-1.74l8-23.7a1.32 1.32 0 0 1 1.249-.9Z");
}

.imt_tccjy {
  d: path("M21.906 3.729a1.32 1.32 0 0 0-1.248-.9h-9.216a1.32 1.32 0 0 1 1.248.9l8 23.7a1.317 1.317 0 0 1-1.248 1.738h9.217a1.317 1.317 0 0 0 1.241-1.738Z");
}

.k05n1gbkm {
  stop-opacity: 0;
}

.l3_3-ephw {
  stop-color: var(--svg-color--3ccbf4, #3ccbf4);
}

.ms0tavq2o {
  stop-color: var(--svg-color--2892df, #2892df);
}

.p_qts-b_r {
  stop-opacity: 0.3;
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

.tugb-hb9z {
  fill: var(--svg-color--0078d4, #0078d4);
  d: path("M23.36 19.894H10.247a.607.607 0 0 0-.414 1.051l8.427 7.865a1.33 1.33 0 0 0 .9.356h7.426Z");
}

.vitvmyb3q {
  d: path("M11.343 2.834a1.31 1.31 0 0 0-1.252.914L2.106 27.407a1.315 1.315 0 0 0 1.241 1.759h6.6a1.41 1.41 0 0 0 1.083-.921l1.592-4.693l5.688 5.306a1.35 1.35 0 0 0 .847.309h7.4l-3.245-9.272h-9.459l5.79-17.061Z");
}

.ws0rd4b2v {
  stop-opacity: 0.05;
}

</style>
