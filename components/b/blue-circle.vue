<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iHE7VLb)" class="mcvyvgbao"/><path fill="url(#iGaW7Ac)" class="mcvyvgbao"/><path fill="url(#iYe4j3b)" class="mcvyvgbao"/><path fill="url(#iq0Sdgd)" class="mcvyvgbao"/><path fill="url(#i5dVf6L)" class="mcvyvgbao"/><defs><radialGradient id="iHE7VLb" cx="0" cy="0" r="1" gradientTransform="rotate(130.168 10.023 9.747)scale(27.8086)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="scwaddb6u"/><stop offset=".853" class="xvccs_xbc"/></radialGradient><radialGradient id="iYe4j3b" cx="0" cy="0" r="1" gradientTransform="rotate(136.38 10.142 10.077)scale(14.6767 15.816)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="y03rdrbgz"/><stop offset="1" class="z5r5b7m7s"/></radialGradient><radialGradient id="iq0Sdgd" cx="0" cy="0" r="1" gradientTransform="matrix(-19.25 0 0 -20 20.249 15.625)" gradientUnits="userSpaceOnUse"><stop offset=".62" class="o8hf7o51v"/><stop offset=".951" class="mi141db7g"/></radialGradient><radialGradient id="i5dVf6L" cx="0" cy="0" r="1" gradientTransform="matrix(0 21 -23.3208 0 15.757 8.625)" gradientUnits="userSpaceOnUse"><stop offset=".863" class="c7py43b2j"/><stop offset="1" class="zr67r_bsb"/></radialGradient><linearGradient id="iGaW7Ac" x1="15.757" x2="15.757" y1="1.625" y2="8.125" gradientUnits="userSpaceOnUse"><stop class="zxoz7bcgt"/><stop offset="1" class="zilsa9wjl"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:blue-circle" /></template>
<style>
.c7py43b2j {
  stop-color: var(--svg-color--3e4dcb, #3E4DCB);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.mcvyvgbao {
  d: path("M29.757 15.625c0 7.732-6.268 14-14 14s-14-6.268-14-14s6.268-14 14-14s14 6.268 14 14");
}

.mi141db7g {
  stop-color: var(--svg-color--859bc6, #859BC6);
}

.o8hf7o51v {
  stop-color: var(--svg-color--416aa9, #416AA9);
  stop-opacity: 0;
}

.scwaddb6u {
  stop-color: var(--svg-color--4da0da, #4DA0DA);
}

.xvccs_xbc {
  stop-color: var(--svg-color--3557c3, #3557C3);
}

.y03rdrbgz {
  stop-color: var(--svg-color--62a5e9, #62A5E9);
}

.z5r5b7m7s {
  stop-color: var(--svg-color--4579d7, #4579D7);
  stop-opacity: 0;
}

.zilsa9wjl {
  stop-color: var(--svg-color--5b9cce, #5B9CCE);
  stop-opacity: 0;
}

.zr67r_bsb {
  stop-color: var(--svg-color--695fd4, #695FD4);
}

.zxoz7bcgt {
  stop-color: var(--svg-color--5b9cce, #5B9CCE);
}

</style>
