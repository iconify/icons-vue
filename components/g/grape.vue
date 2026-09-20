<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient x1="5.177%" y1="21.825%" x2="94.272%" y2="78.175%" id="ssvg-id-grapeb"><stop offset="0%" class="qimhp4b2k"/><stop offset="100%" class="s-tkmob5a"/></linearGradient><linearGradient x1="100%" y1="73.958%" x2="0%" y2="23.824%" id="ssvg-id-graped"><stop offset="0%" class="l7etz4bkw"/><stop offset="58.976%" class="vpu09ddok"/><stop offset="100%" class="nymqonbvq"/></linearGradient><radialGradient cx="71.139%" cy="30.656%" fx="71.139%" fy="30.656%" r="62.855%" id="ssvg-id-grapea"><stop offset="0%" class="ht__06-ac"/><stop offset="100%" class="obp2vbs5m"/><stop offset="100%" class="w_yo1wbgd"/></radialGradient><filter x="-50%" y="-50%" width="200%" height="200%" filterUnits="objectBoundingBox" id="ssvg-id-grapec"><feOffset dx="4" dy="6" in="SourceAlpha" result="shadowOffsetOuter1"/><feGaussianBlur stdDeviation="3" in="shadowOffsetOuter1" result="shadowBlurOuter1"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.21 0" in="shadowBlurOuter1" result="shadowMatrixOuter1"/><feMerge><feMergeNode in="shadowMatrixOuter1"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs><path fill="url(#ssvg-id-grapea)" class="mzywkn9se"/><path fill="url(#ssvg-id-grapeb)" filter="url(#ssvg-id-grapec)" class="umv79vu_a"/><path fill="url(#ssvg-id-graped)" class="x5mw2tq4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:grape" /></template>
<style>
.ht__06-ac {
  stop-color: var(--svg-color--8d5391, #8D5391);
}

.l7etz4bkw {
  stop-color: var(--svg-color--90c567, #90C567);
}

.mzywkn9se {
  d: path("M256 128c0 70.692-57.308 128-128 128C57.308 256 0 198.692 0 128C0 57.308 57.308 0 128 0c70.692 0 128 57.308 128 128");
}

.nymqonbvq {
  stop-color: var(--svg-color--98c871, #98C871);
}

.obp2vbs5m {
  stop-color: var(--svg-color--56185b, #56185B);
}

.qimhp4b2k {
  stop-color: var(--svg-color--6c8a55, #6C8A55);
}

.s-tkmob5a {
  stop-color: var(--svg-color--5e7a44, #5E7A44);
}

.umv79vu_a {
  d: path("M127.002.008c57.887-.083 129.081 58.303 101.801 145.965c-64.54-13.14-113.611-69.697-101.801-145.965");
}

.vpu09ddok {
  stop-color: var(--svg-color--a2ce7f, #A2CE7F);
}

.w_yo1wbgd {
  stop-color: var(--svg-color--55175a, #55175A);
}

.x5mw2tq4t {
  d: path("M146.493 2.096c51.495 9.764 97.905 61.413 86.864 124.41c-52.086-9.289-97.302-57.563-86.864-124.41");
}

</style>
