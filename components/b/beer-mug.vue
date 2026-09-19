<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#itDOPkd)" class="zhzn8lbbd"/><path fill="url(#iJJz0ee)" class="ist1dacay"/><path class="dag5s4b5m"/><g filter="url(#i7y5lcb)"><path class="yjwc14bus"/></g><path class="lzs-65b7v"/><g filter="url(#icLmdKc)"><path class="w-lc6bbqt"/></g><path fill="url(#iTqPdDc)" class="dqkgs1bxw"/><path fill="url(#ir8EDId)" class="dqkgs1bxw"/><path fill="url(#iZVjFdc)" class="dqkgs1bxw"/><path fill="url(#indvg8M)" class="dqkgs1bxw"/><path fill="url(#iYwAKMd)" class="dqkgs1bxw"/><path fill="url(#ijw5b2c)" class="dqkgs1bxw"/><path fill="url(#ih05Kmd)" class="imr1y6bfd"/><path fill="url(#iZbGmUb)" class="h_8o856ti"/><path fill="url(#i6n5Kud)" class="w5w_6jb5v"/><path fill="url(#ihRsYFd)" class="m716htb8c"/><path class="sc-lrfb-y"/><path fill="url(#iSS7rAs)" class="t09yvqi7a"/><path fill="url(#izhwgbc)" class="t09yvqi7a"/><path fill="url(#ibm9Dqc)" class="t09yvqi7a"/><path fill="url(#ib9N5Gd)" class="t09yvqi7a"/><path fill="url(#iciN6Eb)" class="voqyl0b7q"/><g filter="url(#iPXobnb)"><path stroke="url(#iSoXdnd)" class="w3q72kbnd"/></g><g filter="url(#iQM8yVc)"><path class="gihhgsb-z"/></g><defs><radialGradient id="itDOPkd" cx="0" cy="0" r="1" gradientTransform="rotate(113.416 8.865 10.339)scale(8.24119)" gradientUnits="userSpaceOnUse"><stop class="vfgk6i-zc"/><stop offset=".335" class="da9qam_aa"/><stop offset=".907" class="zlwuztpuh"/></radialGradient><radialGradient id="iJJz0ee" cx="0" cy="0" r="1" gradientTransform="rotate(99.138 1.099 7.193)scale(5.95052)" gradientUnits="userSpaceOnUse"><stop offset=".348" class="utnficbun"/><stop offset=".907" class="zlwuztpuh"/></radialGradient><radialGradient id="iZVjFdc" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.5 -9.78107 0 8.625 26.625)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="oevh2ua0n"/><stop offset="1" class="xmxm79b3o"/></radialGradient><radialGradient id="iYwAKMd" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.875 -13.875 0 16.125 10.75)" gradientUnits="userSpaceOnUse"><stop offset=".134" class="apw9-2kbo"/><stop offset=".412" class="i63daeb2q"/><stop offset=".908" class="ac3e04wpq"/></radialGradient><radialGradient id="ijw5b2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.0625 -4.48502 0 17.5 14)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f7qil3imz"/><stop offset="1" class="vvifndkuy"/></radialGradient><radialGradient id="i6n5Kud" cx="0" cy="0" r="1" gradientTransform="rotate(120.897 3.595 15.502)scale(.92445)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="fcomji9ac"/><stop offset=".737" class="g5xm97bdx"/></radialGradient><radialGradient id="ihRsYFd" cx="0" cy="0" r="1" gradientTransform="rotate(120.897 2.225 11.322)scale(.92445)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="rh9vfnvdc"/><stop offset="1" class="zh_pa7bpe"/></radialGradient><radialGradient id="iSS7rAs" cx="0" cy="0" r="1" gradientTransform="matrix(5.25 7.5 -9.64769 6.75338 15.313 4.938)" gradientUnits="userSpaceOnUse"><stop class="frai7hb_p"/><stop offset=".428" class="v7n33ngej"/><stop offset=".593" class="n0avrgb2v"/><stop offset=".751" class="t_6sn14ou"/></radialGradient><radialGradient id="izhwgbc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8 -5.60003 0 12.6 12.813)" gradientUnits="userSpaceOnUse"><stop offset=".279" class="z9cu3vbra"/><stop offset="1" class="g1-68ybmr"/></radialGradient><radialGradient id="ibm9Dqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .59375 -5.125 0 14.75 9.063)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="qwbjbsbiq"/><stop offset="1" class="b4zt42e0h"/></radialGradient><radialGradient id="ib9N5Gd" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.92236 -3.85752 0 10.188 14.64)" gradientUnits="userSpaceOnUse"><stop class="r4jgjva1a"/><stop offset="1" class="cx0sf40ak"/></radialGradient><radialGradient id="iciN6Eb" cx="0" cy="0" r="1" gradientTransform="rotate(120.897 6.24 10.991)scale(1.33886)" gradientUnits="userSpaceOnUse"><stop offset=".077" class="biomudb-n"/><stop offset=".737" class="b9eryabuu"/></radialGradient><linearGradient id="iTqPdDc" x1="4.974" x2="20.8" y1="19.839" y2="19.839" gradientUnits="userSpaceOnUse"><stop class="sj3n6yb8g"/><stop offset=".085" class="u2v899b4v"/><stop offset=".262" class="hn6q58bqh"/><stop offset=".491" class="h1e-c9b1j"/><stop offset=".582" class="gmai51v0j"/><stop offset=".878" class="hefw-7b0q"/><stop offset="1" class="c9ivcibuu"/></linearGradient><linearGradient id="ir8EDId" x1="11.875" x2="20.8" y1="22.875" y2="22.875" gradientUnits="userSpaceOnUse"><stop offset=".099" class="pyk17pb9p"/><stop offset=".331" class="i_9rrzbjk"/><stop offset=".581" class="nn5eievjk"/><stop offset=".875" class="hy4k2vbel"/><stop offset="1" class="k0r1mpbyx"/></linearGradient><linearGradient id="indvg8M" x1="13.015" x2="13.015" y1="26.813" y2="27.88" gradientUnits="userSpaceOnUse"><stop class="hzg1gb40j"/><stop offset="1" class="g58kgk0pu"/></linearGradient><linearGradient id="ih05Kmd" x1="10.02" x2="10.02" y1="12.63" y2="25.01" gradientUnits="userSpaceOnUse"><stop offset=".121" class="knq-knezv"/><stop offset=".383" class="j5rg3dysz"/><stop offset="1" class="zv_q4abtk"/></linearGradient><linearGradient id="iZbGmUb" x1="16.02" x2="16.02" y1="12.63" y2="25.01" gradientUnits="userSpaceOnUse"><stop class="yh27mxb0l"/><stop offset=".272" class="wah-3fbwn"/><stop offset=".57" class="r3b9vibmk"/><stop offset="1" class="xwfccwbtw"/></linearGradient><linearGradient id="iSoXdnd" x1="27.858" x2="27.858" y1="12.092" y2="22.018" gradientUnits="userSpaceOnUse"><stop class="e3lc5kbwv"/><stop offset=".711" class="g1f8mubpw"/><stop offset="1" class="k4pw0yjeb"/></linearGradient><filter id="i7y5lcb" width="12.809" height="14.548" x="16.316" y="10.737" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33005" stdDeviation=".25"/></filter><filter id="icLmdKc" width="20.844" height="22.125" x="2.625" y="8.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33005" stdDeviation=".5"/></filter><filter id="iPXobnb" width="2.378" height="11.426" x="26.669" y="11.342" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33005" stdDeviation=".25"/></filter><filter id="iQM8yVc" width="1.517" height="9.381" x="25.872" y="13.387" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33005" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:beer-mug" /></template>
<style>
.ac3e04wpq {
  stop-color: var(--svg-color--e9a442, #E9A442);
  stop-opacity: 0;
}

.apw9-2kbo {
  stop-color: var(--svg-color--fff09e, #FFF09E);
}

.b4zt42e0h {
  stop-color: var(--svg-color--d7bee1, #D7BEE1);
  stop-opacity: 0;
}

.b9eryabuu {
  stop-color: var(--svg-color--ffc56d, #FFC56D);
}

.biomudb-n {
  stop-color: var(--svg-color--ffe57b, #FFE57B);
}

.c9ivcibuu {
  stop-color: var(--svg-color--f5bf7f, #F5BF7F);
}

.cx0sf40ak {
  stop-color: var(--svg-color--d1bee5, #D1BEE5);
  stop-opacity: 0;
}

.da9qam_aa {
  stop-color: var(--svg-color--edebef, #EDEBEF);
}

.dag5s4b5m {
  fill: var(--svg-color--bdd9f5, #BDD9F5);
  d: path("M25.218 13.973c.41 0 .735.333.735.73v6.547c0 .408-.303.691-.703.691h-5.38c-.41 0-.734-.294-.734-.691v-6.547c0-.408.335-.73.735-.73zm.629-3H19.87a3.08 3.08 0 0 0-3.091 3.07v7.898a3.08 3.08 0 0 0 3.09 3.07h5.977a3.08 3.08 0 0 0 3.09-3.07v-7.898a3.08 3.08 0 0 0-3.09-3.07");
}

.dqkgs1bxw {
  d: path("M5.23 27.05V9H20.8v18.05c0 .46-.37.83-.83.83H6.06c-.46 0-.83-.37-.83-.83");
}

.e3lc5kbwv {
  stop-color: var(--svg-color--dffcff, #DFFCFF);
}

.f7qil3imz {
  stop-color: var(--svg-color--fff29a, #FFF29A);
}

.fcomji9ac {
  stop-color: var(--svg-color--ffc579, #FFC579);
}

.frai7hb_p {
  stop-color: var(--svg-color--f8f7f9, #F8F7F9);
}

.ft5dv1b6b {
  fill: none;
}

.g1-68ybmr {
  stop-color: var(--svg-color--d1c8dc, #D1C8DC);
  stop-opacity: 0;
}

.g1f8mubpw {
  stop-color: var(--svg-color--d4f6ff, #D4F6FF);
}

.g58kgk0pu {
  stop-color: var(--svg-color--d567ab, #D567AB);
}

.g5xm97bdx {
  stop-color: var(--svg-color--ffa672, #FFA672);
}

.gihhgsb-z {
  stroke: var(--svg-color--cef0ff, #CEF0FF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M26.622 14.137c0 .51.016 4.964.016 7.881");
}

.gmai51v0j {
  stop-color: var(--svg-color--ffae78, #FFAE78);
}

.h_8o856ti {
  d: path("M16.02 25.01c-.55 0-1-.45-1-1V13.63c0-.55.45-1 1-1s1 .45 1 1v10.38c0 .55-.45 1-1 1");
}

.h1e-c9b1j {
  stop-color: var(--svg-color--f8a369, #F8A369);
}

.hefw-7b0q {
  stop-color: var(--svg-color--ffcf86, #FFCF86);
}

.hn6q58bqh {
  stop-color: var(--svg-color--dd9642, #DD9642);
}

.hy4k2vbel {
  stop-color: var(--svg-color--ffc990, #FFC990);
}

.hzg1gb40j {
  stop-color: var(--svg-color--da6788, #DA6788);
  stop-opacity: 0;
}

.i_9rrzbjk {
  stop-color: var(--svg-color--fba582, #FBA582);
}

.i63daeb2q {
  stop-color: var(--svg-color--ffd57f, #FFD57F);
}

.imr1y6bfd {
  d: path("M10.02 25.01c-.55 0-1-.45-1-1V13.63c0-.55.45-1 1-1s1 .45 1 1v10.38c0 .55-.45 1-1 1");
}

.ist1dacay {
  d: path("M7.43 12.88a4.43 4.43 0 1 0 0-8.86a4.43 4.43 0 0 0 0 8.86");
}

.j5rg3dysz {
  stop-color: var(--svg-color--f6b56f, #F6B56F);
}

.k0r1mpbyx {
  stop-color: var(--svg-color--ebae82, #EBAE82);
}

.k4pw0yjeb {
  stop-color: var(--svg-color--defdff, #DEFDFF);
  stop-opacity: 0;
}

.knq-knezv {
  stop-color: var(--svg-color--feb861, #FEB861);
}

.lzs-65b7v {
  fill: var(--svg-color--c1d6f0, #C1D6F0);
  d: path("M3 9.03v18.03c0 1.66 1.38 3 3.07 3h13.89c1.69 0 3.07-1.35 3.07-3V9.03z");
}

.m716htb8c {
  d: path("M12.79 16.02a.58.58 0 1 0 0-1.16a.58.58 0 0 0 0 1.16");
}

.n0avrgb2v {
  stop-color: var(--svg-color--d2c9db, #D2C9DB);
}

.nn5eievjk {
  stop-color: var(--svg-color--ffbe9f, #FFBE9F);
}

.oevh2ua0n {
  stop-color: var(--svg-color--bf634c, #BF634C);
}

.pyk17pb9p {
  stop-color: var(--svg-color--f9a27c, #F9A27C);
  stop-opacity: 0;
}

.qwbjbsbiq {
  stop-color: var(--svg-color--d7bee2, #D7BEE2);
}

.r3b9vibmk {
  stop-color: var(--svg-color--ffeabc, #FFEABC);
}

.r4jgjva1a {
  stop-color: var(--svg-color--d2bbe5, #D2BBE5);
}

.rh9vfnvdc {
  stop-color: var(--svg-color--ffd96c, #FFD96C);
}

.sc-lrfb-y {
  fill: var(--svg-color--bcbbbc, #BCBBBC);
  d: path("M17.61 7.01c0-2.78-2.26-5.03-5.05-5.01c-2.76.02-4.97 2.31-4.97 5.08v5.05c0 1.38 1.12 2.51 2.51 2.51c1.38 0 2.51-1.12 2.51-2.51v-1.66C12.6 9.66 13.26 9 14.07 9h3.13c.27-.61.41-1.28.41-1.99");
}

.sj3n6yb8g {
  stop-color: var(--svg-color--be986c, #BE986C);
}

.t_6sn14ou {
  stop-color: var(--svg-color--d7d2dc, #D7D2DC);
  stop-opacity: 0;
}

.t09yvqi7a {
  d: path("M17.61 7.01c0-2.78-2.26-5.03-5.05-5.01c-2.76.02-4.97 2.31-4.97 5.08v5.05c0 1.38 1.12 2.51 2.51 2.51c1.38 0 2.51-1.12 2.51-2.51v-1.66C12.6 9.66 13.26 9 14.07 9h3.13c.27-.61.41-1.28.41-1.99");
}

.u2v899b4v {
  stop-color: var(--svg-color--cd9658, #CD9658);
}

.utnficbun {
  stop-color: var(--svg-color--e8e5ec, #E8E5EC);
}

.v7n33ngej {
  stop-color: var(--svg-color--e2dbe9, #E2DBE9);
}

.vfgk6i-zc {
  stop-color: var(--svg-color--f6f5f7, #F6F5F7);
}

.voqyl0b7q {
  d: path("M18.45 12.43a.84.84 0 1 0 0-1.68a.84.84 0 0 0 0 1.68");
}

.vvifndkuy {
  stop-color: var(--svg-color--ffe492, #FFE492);
  stop-opacity: 0;
}

.w-lc6bbqt {
  fill: var(--svg-color--c9ebff, #C9EBFF);
  d: path("M3.625 9.438v17.254a2.88 2.88 0 0 0 2.888 2.87h13.068c1.59 0 2.888-1.291 2.888-2.87V9.438z");
}

.w3q72kbnd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M27.42 12.092c.387.251.86 1 .86 1.509c0 .51.017 5.5.017 8.417");
}

.w5w_6jb5v {
  d: path("M18.45 21.17a.58.58 0 1 0 0-1.16a.58.58 0 0 0 0 1.16");
}

.wah-3fbwn {
  stop-color: var(--svg-color--ffecaa, #FFECAA);
}

.xmxm79b3o {
  stop-color: var(--svg-color--f09771, #F09771);
  stop-opacity: 0;
}

.xwfccwbtw {
  stop-color: var(--svg-color--ffe8ce, #FFE8CE);
}

.yh27mxb0l {
  stop-color: var(--svg-color--fff19e, #FFF19E);
}

.yjwc14bus {
  fill: var(--svg-color--c7edff, #C7EDFF);
  d: path("M25.219 13.563c1.045 0 1.045.671 1.045 1.374v6.141c0 .813-.338 1.14-1.327 1.14h-5.251c-.368 0-.76-.333-.76-.689v-7.074c0-.365.3-.893.659-.893zm0-2.326h-5.635c-1.529 0-2.768 1.7-2.768 3.218v7.074c0 1.519 1.24 3.256 2.768 3.256h5.353c2.516 0 3.688-1.285 3.688-2.884v-7.446c0-1.743-1.078-3.218-3.406-3.218");
}

.z9cu3vbra {
  stop-color: var(--svg-color--fff7ff, #FFF7FF);
}

.zh_pa7bpe {
  stop-color: var(--svg-color--f3a857, #F3A857);
}

.zhzn8lbbd {
  d: path("M18.6 12.88a4.43 4.43 0 1 0 0-8.86a4.43 4.43 0 0 0 0 8.86");
}

.zlwuztpuh {
  stop-color: var(--svg-color--bab9bb, #BAB9BB);
}

.zv_q4abtk {
  stop-color: var(--svg-color--f2c3aa, #F2C3AA);
}

</style>
