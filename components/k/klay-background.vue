<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGu70OaedF)" class="r4i437pya"/><path class="p91l3dwkm"/><path class="hfhehwb2y"/><path class="zw8qv0bcj"/><path class="wa_258_yk"/><path class="mbc29wbks"/></g><defs><linearGradient id="SVGu70OaedF" x1="10.794" x2="10.794" y1="4" y2="27.715" gradientUnits="userSpaceOnUse"><stop class="ykx3y_agn"/><stop offset=".51" class="fv8rocleq"/><stop offset="1" class="nwfxn8bpn"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:klay-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.fv8rocleq {
  stop-color: var(--svg-color--e91a00, #e91a00);
}

.hfhehwb2y {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.286 4c1.8.045 3.475.695 4.845 1.865l-8.915 8.93zm.73 8.02l5.14-5.16a8.085 8.085 0 0 1 0 10.28z");
}

.mbc29wbks {
  fill: var(--svg-color--fff, #fff);
  d: path("m6.886 18.135l5.145-5.116l5.14 5.116A8 8 0 0 1 12.03 20a8 8 0 0 1-5.145-1.865");
}

.nwfxn8bpn {
  stop-color: var(--svg-color--7c0000, #7c0000);
}

.p91l3dwkm {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.286 4c1.8.045 3.475.695 4.845 1.865l-8.915 8.93z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.wa_258_yk {
  fill: var(--svg-color--fff, #fff);
  d: path("m4.015 11.5l6.26-6.285l-4.46 11.88a8.06 8.06 0 0 1-1.8-5.595m2.871 6.635l5.145-5.116l5.14 5.116A8 8 0 0 1 12.03 20a8 8 0 0 1-5.145-1.865");
}

.ykx3y_agn {
  stop-color: var(--svg-color--ff8300, #ff8300);
}

.zw8qv0bcj {
  fill: var(--svg-color--fff, #fff);
  d: path("m13.016 12.02l5.14-5.16a8.085 8.085 0 0 1 0 10.28zm-9.001-.52l6.26-6.285l-4.46 11.88a8.06 8.06 0 0 1-1.8-5.595");
}

</style>
