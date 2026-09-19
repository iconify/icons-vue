<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="xrmx78b0x"/><path fill="url(#iuIXiCd)" class="jtgbvnr2s"/><path fill="url(#iGZXpEb)" class="jtgbvnr2s"/><path fill="url(#iKR1yze)" class="nquy_ibss"/><path fill="url(#iXp3Bpq)" class="nquy_ibss"/><path fill="url(#iQBVQBb)" class="nquy_ibss"/><defs><radialGradient id="iuIXiCd" cx="0" cy="0" r="1" gradientTransform="matrix(0 10 -21.9715 0 16 30.75)" gradientUnits="userSpaceOnUse"><stop class="r26lylgpi"/><stop offset=".632" class="hiadncb5q"/></radialGradient><radialGradient id="iGZXpEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.2025 -17.75 0 25.75 22.25)" gradientUnits="userSpaceOnUse"><stop offset=".087" class="wknkl5bah"/><stop offset=".694" class="lg7u9bumu"/></radialGradient><radialGradient id="iXp3Bpq" cx="0" cy="0" r="1" gradientTransform="matrix(.125 7.25 -14.51844 .25033 23.5 18.25)" gradientUnits="userSpaceOnUse"><stop class="djmivgb_f"/><stop offset=".509" class="rg-0q8byc"/><stop offset="1" class="awwp1gbxc"/></radialGradient><radialGradient id="iQBVQBb" cx="0" cy="0" r="1" gradientTransform="matrix(.62492 10.50002 -24.15316 1.4375 12.626 24)" gradientUnits="userSpaceOnUse"><stop class="b22is5bkr"/><stop offset="1" class="xcutevbjj"/></radialGradient><linearGradient id="iKR1yze" x1="24.125" x2="2" y1="9.875" y2="18.25" gradientUnits="userSpaceOnUse"><stop class="tqlbvpbkj"/><stop offset=".549" class="bdy_jjb2s"/><stop offset=".871" class="smmrb4s5g"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:chestnut" /></template>
<style>
.awwp1gbxc {
  stop-color: var(--svg-color--744450, #744450);
  stop-opacity: 0;
}

.b22is5bkr {
  stop-color: var(--svg-color--693848, #693848);
}

.bdy_jjb2s {
  stop-color: var(--svg-color--643e38, #643E38);
}

.djmivgb_f {
  stop-color: var(--svg-color--9a7772, #9A7772);
}

.ft5dv1b6b {
  fill: none;
}

.hiadncb5q {
  stop-color: var(--svg-color--cd6c75, #CD6C75);
  stop-opacity: 0;
}

.jtgbvnr2s {
  d: path("M29.68 22.173L16 17L2.32 22.172c1.04 3.97 4.52 7.28 9.39 7.28h8.57c4.88 0 8.36-3.31 9.4-7.28");
}

.lg7u9bumu {
  stop-color: var(--svg-color--eca27a, #ECA27A);
  stop-opacity: 0;
}

.nquy_ibss {
  d: path("M29.68 22.173c.83-3.16.11-6.75-2.69-9.42l-9.59-9.19c-.78-.75-2.02-.75-2.8 0l-9.59 9.19c-2.8 2.68-3.51 6.26-2.69 9.42z");
}

.r26lylgpi {
  stop-color: var(--svg-color--cc6b7e, #CC6B7E);
}

.rg-0q8byc {
  stop-color: var(--svg-color--916e69, #916E69);
  stop-opacity: 0.4;
}

.smmrb4s5g {
  stop-color: var(--svg-color--5a403c, #5A403C);
}

.tqlbvpbkj {
  stop-color: var(--svg-color--835c55, #835C55);
}

.wknkl5bah {
  stop-color: var(--svg-color--e7a277, #E7A277);
}

.xcutevbjj {
  stop-color: var(--svg-color--7b4552, #7B4552);
  stop-opacity: 0;
}

.xrmx78b0x {
  fill: var(--svg-color--d88578, #D88578);
  d: path("M29.68 22.173L16 17L2.32 22.172c1.04 3.97 4.52 7.28 9.39 7.28h8.57c4.88 0 8.36-3.31 9.4-7.28");
}

</style>
