<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ia2BH8c)"><path fill="url(#it77Izb)" class="psx10hb_y"/><path fill="url(#iTsIbqb)" class="psx10hb_y"/><path fill="url(#ipjspTd)" class="psx10hb_y"/><path fill="url(#iVEJWRd)" class="psx10hb_y"/><path fill="url(#iOGaqrD)" class="psx10hb_y"/></g><path fill="url(#iubbv8c)" class="vlmmw3b4b"/><path fill="url(#iVLaaZl)" class="vlmmw3b4b"/><g filter="url(#iSP4JDc)"><rect fill="url(#iRVeZRd)" class="r4e1i-c9p"/></g><g filter="url(#iptcfZA)"><rect fill="url(#i2PFZZd)" transform="rotate(-51.165 22.317 12.946)" class="yri2ekbvr"/></g><g filter="url(#iN5AFHb)"><rect class="glt_fizxc"/></g><g filter="url(#i20NwZi)"><rect class="l2afofbij"/></g><g filter="url(#i8LtMTd)"><rect class="cfrnoc8vu"/></g><defs><filter id="ia2BH8c" width="26.537" height="28.714" x="3.801" y="1.268" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.513726 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5429"/></filter><filter id="iSP4JDc" width="4.47" height="15.258" x="18.779" y="14.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5429" stdDeviation=".75"/></filter><filter id="iptcfZA" width="8.571" height="7.842" x="21.188" y="10.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5429" stdDeviation=".75"/></filter><filter id="iN5AFHb" width="3.788" height="5.164" x="5.149" y="16.968" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5429" stdDeviation=".5"/></filter><filter id="i20NwZi" width="3.788" height="5.164" x="9.791" y="17.965" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5429" stdDeviation=".5"/></filter><filter id="i8LtMTd" width="3.788" height="5.164" x="14.106" y="18.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5429" stdDeviation=".5"/></filter><linearGradient id="iTsIbqb" x1="1.587" x2="22.874" y1="14.105" y2="14.105" gradientUnits="userSpaceOnUse"><stop class="gumabjbtt"/><stop offset=".293" class="ysq4o442u"/></linearGradient><linearGradient id="iubbv8c" x1="16.657" x2="19.98" y1="24.54" y2="24.54" gradientUnits="userSpaceOnUse"><stop class="h2_n5ruzy"/><stop offset="1" class="yh75rqmjv"/></linearGradient><linearGradient id="iVLaaZl" x1="19.025" x2="19.025" y1="19.49" y2="22.55" gradientUnits="userSpaceOnUse"><stop class="ao4aftbnr"/><stop offset="1" class="gu6r0gbra"/></linearGradient><linearGradient id="iRVeZRd" x1="21.014" x2="21.014" y1="12.667" y2="28.258" gradientUnits="userSpaceOnUse"><stop class="oih2nzbsq"/><stop offset="1" class="v3jqojv9j"/></linearGradient><linearGradient id="i2PFZZd" x1="23.231" x2="23.231" y1="11.142" y2="19.579" gradientUnits="userSpaceOnUse"><stop class="rf5xkc8ne"/><stop offset="1" class="kw313ubae"/></linearGradient><radialGradient id="it77Izb" cx="0" cy="0" r="1" gradientTransform="rotate(130.04 9.066 8.806)scale(21.6737 31.9334)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="rxiiszonf"/><stop offset="1" class="hxqjcsrur"/></radialGradient><radialGradient id="ipjspTd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.35578 6.50892 -15.3421 -14.98115 26.152 7.277)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="zb7irh_hj"/><stop offset="1" class="xfi0u0bsu"/></radialGradient><radialGradient id="iVEJWRd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.19151 2.37896 0 8.08 22.57)" gradientUnits="userSpaceOnUse"><stop class="f-lyvkb5x"/><stop offset="1" class="hc7nzcb2s"/></radialGradient><radialGradient id="iOGaqrD" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.94495 2.95871 0 12.724 23.598)" gradientUnits="userSpaceOnUse"><stop class="f-lyvkb5x"/><stop offset="1" class="hc7nzcb2s"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:backhand-index-pointing-down" /></template>
<style>
.ao4aftbnr {
  stop-color: var(--svg-color--ffc13a, #FFC13A);
}

.cfrnoc8vu {
  width: 1.788px;
  height: 3.164px;
  x: 15.106px;
  y: 19.91px;
  fill: var(--svg-color--ffc045, #FFC045);
  rx: 0.894px;
}

.f-lyvkb5x {
  stop-color: var(--svg-color--eb7b5d, #EB7B5D);
}

.ft5dv1b6b {
  fill: none;
}

.glt_fizxc {
  width: 1.788px;
  height: 3.164px;
  x: 6.149px;
  y: 17.968px;
  fill: var(--svg-color--ffc045, #FFC045);
  rx: 0.894px;
}

.gu6r0gbra {
  stop-color: var(--svg-color--ffc83c, #FFC83C);
  stop-opacity: 0;
}

.gumabjbtt {
  stop-color: var(--svg-color--f4a524, #F4A524);
}

.h2_n5ruzy {
  stop-color: var(--svg-color--e7942d, #E7942D);
}

.hc7nzcb2s {
  stop-color: var(--svg-color--eb7b5d, #EB7B5D);
  stop-opacity: 0;
}

.hxqjcsrur {
  stop-color: var(--svg-color--fdb236, #FDB236);
}

.kw313ubae {
  stop-color: var(--svg-color--ffe548, #FFE548);
}

.l2afofbij {
  width: 1.788px;
  height: 3.164px;
  x: 10.791px;
  y: 18.965px;
  fill: var(--svg-color--ffc045, #FFC045);
  rx: 0.894px;
}

.oih2nzbsq {
  stop-color: var(--svg-color--ffdc45, #FFDC45);
  stop-opacity: 0;
}

.psx10hb_y {
  d: path("M28.042 13.88c1.24.86 1.702 2.597.888 3.849a2.657 2.657 0 0 1-3.702.781l-2.61-1.695v10.53a2.637 2.637 0 1 1-5.274 0v-4.284a2.494 2.494 0 0 1-4.564-.344a2.724 2.724 0 0 1-4.487-.884a2.723 2.723 0 0 1-4.493-2.07v-3.102l.002-.104v-4.859c0-1.431.849-3.878 2.51-6.022q.25-.33.527-.637l.01-.013a9.2 9.2 0 0 1 6.833-3.008a9.2 9.2 0 0 1 7.577 3.945c.603.832.892 1.506 1.178 2.175c.22.513.438 1.023.797 1.601c.566.913 1.4 1.59 1.865 1.969l.098.08h-.002z");
}

.r4e1i-c9p {
  width: 1.47px;
  height: 12.258px;
  x: 20.279px;
  y: 16px;
  rx: 0.735px;
}

.rf5xkc8ne {
  stop-color: var(--svg-color--ffe548, #FFE548);
  stop-opacity: 0;
}

.rxiiszonf {
  stop-color: var(--svg-color--ffd43e, #FFD43E);
}

.v3jqojv9j {
  stop-color: var(--svg-color--ffdc45, #FFDC45);
}

.vlmmw3b4b {
  d: path("M17.344 19.49v7.855a2.637 2.637 0 1 0 5.273 0V19.49z");
}

.xfi0u0bsu {
  stop-color: var(--svg-color--ffe040, #FFE040);
  stop-opacity: 0;
}

.yh75rqmjv {
  stop-color: var(--svg-color--e7942d, #E7942D);
  stop-opacity: 0;
}

.yri2ekbvr {
  width: 1.828px;
  height: 6.633px;
  x: 22.317px;
  y: 12.946px;
  rx: 0.914px;
}

.ysq4o442u {
  stop-color: var(--svg-color--f4a524, #F4A524);
  stop-opacity: 0;
}

.zb7irh_hj {
  stop-color: var(--svg-color--ffe040, #FFE040);
}

</style>
