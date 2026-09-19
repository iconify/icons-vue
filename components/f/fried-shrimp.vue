<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="zcklf9bhv"/><path fill="url(#iVSddue)" class="mjmd3uius"/><path fill="url(#iQkeBUj)" class="i_eu8hd2p"/><path fill="url(#i7ouw0q)" class="iai1kbcjr"/><path class="ad4xw3u-n"/><path fill="url(#ibnyEme)" class="npbte4blh"/><path fill="url(#iEL8w6c)" class="npbte4blh"/><path fill="url(#iuxuOie)" class="npbte4blh"/><path fill="url(#iNquHmd)" class="npbte4blh"/><path fill="url(#iaYZgRb)" class="npbte4blh"/><path fill="url(#iQKs7pb)" class="npbte4blh"/><path fill="url(#iBJEbhe)" class="jagtaxbjv"/><path fill="url(#i4PxVkd)" class="quslypbnc"/><path fill="url(#iiHaoGd)" class="g1g3vi8fy"/><g filter="url(#iAuRpfc)"><path class="ep_xpc8_d"/></g><g filter="url(#ihtcEJe)"><path fill="url(#ioVwoMd)" class="g4xhlsb8d"/></g><g filter="url(#iRF3eeY)"><path stroke="url(#iwKXizd)" class="ksafu5i5r"/></g><g filter="url(#iKJr9oe)"><path stroke="url(#iwKXizd)" class="w7dwk1bxr"/></g><g filter="url(#iLGV5cb)"><path stroke="url(#iYqF6fd)" class="ng50o3b4p"/></g><g filter="url(#iXx9sTI)"><path stroke="url(#i79k0Hd)" class="xdhgtcb5f"/></g><g filter="url(#i6sF0Kd)"><path stroke="url(#iEBo3qb)" class="yor3y3bqw"/></g><defs><radialGradient id="iVSddue" cx="0" cy="0" r="1" gradientTransform="rotate(90.924 .229 13.019)scale(15.502 9.3758)" gradientUnits="userSpaceOnUse"><stop offset=".586" class="s06g_9bfd"/><stop offset=".86" class="ais13vbso"/><stop offset="1" class="clusenbxn"/></radialGradient><radialGradient id="ibnyEme" cx="0" cy="0" r="1" gradientTransform="matrix(.375 12.24996 -12.27945 .3759 17.25 8.2)" gradientUnits="userSpaceOnUse"><stop offset=".211" class="zjwaehbsp"/><stop offset=".597" class="nq57subgg"/><stop offset="1" class="pom_j7bfz"/></radialGradient><radialGradient id="iEL8w6c" cx="0" cy="0" r="1" gradientTransform="matrix(17.625 10.8125 -7.11731 11.60163 26.625 15.063)" gradientUnits="userSpaceOnUse"><stop offset=".741" class="kunikvhbc"/><stop offset=".849" class="sys2tebvs"/></radialGradient><radialGradient id="iuxuOie" cx="0" cy="0" r="1" gradientTransform="matrix(12.0625 -1.7 .97286 6.90303 12.875 24.2)" gradientUnits="userSpaceOnUse"><stop offset=".149" class="hb9s3wbxt"/><stop offset=".559" class="sh1u5ab0i"/><stop offset=".787" class="dqy3qre5v"/><stop offset="1" class="nyeg3ej3p"/></radialGradient><radialGradient id="iNquHmd" cx="0" cy="0" r="1" gradientTransform="rotate(82.51 2.21 13.947)scale(31.645 21.0895)" gradientUnits="userSpaceOnUse"><stop offset=".528" class="pd9gmgghz"/><stop offset=".606" class="l87ek2beb"/><stop offset=".633" class="pkfzjdbgk"/></radialGradient><radialGradient id="iaYZgRb" cx="0" cy="0" r="1" gradientTransform="matrix(.56252 44.31253 -11.85824 .15053 18.688 11.75)" gradientUnits="userSpaceOnUse"><stop offset=".568" class="i612cac2f"/><stop offset=".739" class="ec4w96bvg"/></radialGradient><radialGradient id="iQKs7pb" cx="0" cy="0" r="1" gradientTransform="matrix(.125 3.8125 -7.1105 .23313 12.375 17.375)" gradientUnits="userSpaceOnUse"><stop class="nvwsbdn3q"/><stop offset="1" class="twrhtrbad"/></radialGradient><radialGradient id="iBJEbhe" cx="0" cy="0" r="1" gradientTransform="rotate(130.266 4.649 9.178)scale(1.59552)" gradientUnits="userSpaceOnUse"><stop offset=".153" class="l2nnv6ofr"/><stop offset="1" class="xmcx18bah"/></radialGradient><radialGradient id="i4PxVkd" cx="0" cy="0" r="1" gradientTransform="rotate(129.009 6.462 10.177)scale(2.18449)" gradientUnits="userSpaceOnUse"><stop class="bxm-jkb5b"/><stop offset="1" class="rvbr40bnw"/></radialGradient><radialGradient id="iiHaoGd" cx="0" cy="0" r="1" gradientTransform="rotate(136.736 6.988 7.183)scale(2.91815)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="qysx3lb4z"/><stop offset="1" class="y2wtsnj4m"/></radialGradient><radialGradient id="i79k0Hd" cx="0" cy="0" r="1" gradientTransform="rotate(50.755 -4.12 9.177)scale(1.43248 1.88484)" gradientUnits="userSpaceOnUse"><stop class="tv-do7hac"/><stop offset="1" class="v1rov3uzm"/></radialGradient><radialGradient id="iEBo3qb" cx="0" cy="0" r="1" gradientTransform="rotate(129.245 3.264 5.568)scale(1.43248 1.88484)" gradientUnits="userSpaceOnUse"><stop class="gwg1vu18c"/><stop offset="1" class="v1rov3uzm"/></radialGradient><filter id="iAuRpfc" width="9.838" height="14.838" x="5.313" y="11.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30826" stdDeviation=".75"/></filter><filter id="ihtcEJe" width="5.381" height="9.834" x="4.872" y="5.747" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30826" stdDeviation=".15"/></filter><filter id="iRF3eeY" width="2.708" height="1.667" x="4.795" y="12.244" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30826" stdDeviation=".25"/></filter><filter id="iKJr9oe" width="2.664" height="1.47" x="4.82" y="12.242" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30826" stdDeviation=".25"/></filter><filter id="iLGV5cb" width="2.612" height="1.637" x="7.53" y="12.244" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30826" stdDeviation=".25"/></filter><filter id="iXx9sTI" width="2.192" height="1.865" x="5.015" y="5.814" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30826" stdDeviation=".125"/></filter><filter id="i6sF0Kd" width="2.192" height="1.865" x="8.028" y="5.814" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_30826" stdDeviation=".125"/></filter><linearGradient id="iQkeBUj" x1="14.432" x2="14.506" y1="29.974" y2="29.846" gradientUnits="userSpaceOnUse"><stop class="p475_abra"/><stop offset="1" class="i46bc3-mx"/></linearGradient><linearGradient id="i7ouw0q" x1="14.257" x2="14.269" y1="29.901" y2="29.88" gradientUnits="userSpaceOnUse"><stop class="p475_abra"/><stop offset="1" class="i46bc3-mx"/></linearGradient><linearGradient id="ioVwoMd" x1="10.375" x2="7.531" y1="7.25" y2="15.281" gradientUnits="userSpaceOnUse"><stop offset=".705" class="hfz5mufid"/><stop offset="1" class="j1dd-v1ax"/></linearGradient><linearGradient id="iwKXizd" x1="6.969" x2="4.734" y1="12.891" y2="13.266" gradientUnits="userSpaceOnUse"><stop offset=".217" class="t-di_ibdb"/><stop offset="1" class="oodbhcj6a"/></linearGradient><linearGradient id="iYqF6fd" x1="8.063" x2="10.297" y1="12.891" y2="13.266" gradientUnits="userSpaceOnUse"><stop offset=".217" class="t-di_ibdb"/><stop offset="1" class="oodbhcj6a"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:fried-shrimp" /></template>
<style>
.ad4xw3u-n {
  fill: var(--svg-color--f89331, #F89331);
  d: path("M18.59 2.95a7.08 7.08 0 0 0-7.08 7.08v1.1a5.97 5.97 0 0 0 2.81 5.07c.79.49 1.25 1.37 1.25 2.3v.63c0 1.32-.74 2.17-1.68 2.53v8.2c.67.09 1.37.13 2.08.14c6.07.02 11.02-4.92 11.02-10.99v-7.66c-.01-4.64-3.77-8.4-8.4-8.4");
}

.ais13vbso {
  stop-color: var(--svg-color--ff4a3b, #FF4A3B);
}

.bxm-jkb5b {
  stop-color: var(--svg-color--ff8b44, #FF8B44);
}

.clusenbxn {
  stop-color: var(--svg-color--d8314e, #D8314E);
}

.dqy3qre5v {
  stop-color: var(--svg-color--f8953f, #F8953F);
}

.ec4w96bvg {
  stop-color: var(--svg-color--d37d35, #D37D35);
}

.ep_xpc8_d {
  fill: var(--svg-color--ff876d, #FF876D);
  d: path("M8.813 14.25a1 1 0 1 0-2 0zm3.59 10.71l.993.128l.254-1.984l-.991-.127zm-4.278-5.21l-.985.17zm-1.312-5.5c0 1.544-.003 3.758.327 5.67l1.97-.34c-.295-1.713-.297-3.75-.297-5.33zm.327 5.67c.228 1.327.508 2.56 1.353 3.467c.866.93 2.151 1.348 3.91 1.574l.256-1.984c-1.647-.212-2.332-.556-2.702-.954c-.391-.42-.611-1.077-.847-2.443z");
}

.ft5dv1b6b {
  fill: none;
}

.g1g3vi8fy {
  d: path("M15.81 10.02a1.71 1.71 0 1 0 0-3.42a1.71 1.71 0 0 0 0 3.42");
}

.g4xhlsb8d {
  d: path("M8.016 7.953c0-1.125 1.395-1.729 1.937-1.906v7.11L8.188 15.28h-1.22l-1.795-2.03V6.11c1.225 0 1.927 1.197 1.937 1.843v4.633c0 .125-.021.57.454.57c.474 0 .388-.445.398-.57c0-1.115.055-3.508.055-4.633");
}

.gwg1vu18c {
  stop-color: var(--svg-color--ffb374, #FFB374);
}

.hb9s3wbxt {
  stop-color: var(--svg-color--ffe24f, #FFE24F);
}

.hfz5mufid {
  stop-color: var(--svg-color--ff8b52, #FF8B52);
}

.i_eu8hd2p {
  d: path("m14.29 29.89l.35.03c-.11 0-.23-.01-.35-.03");
}

.i46bc3-mx {
  stop-color: var(--svg-color--ff8c00, #FF8C00);
}

.i612cac2f {
  stop-color: var(--svg-color--c07a47, #C07A47);
  stop-opacity: 0;
}

.iai1kbcjr {
  d: path("M14.23 29.89c.02 0 .04 0 .06.01c-.02-.01-.04-.01-.06-.01");
}

.j1dd-v1ax {
  stop-color: var(--svg-color--ff8b52, #FF8B52);
  stop-opacity: 0;
}

.jagtaxbjv {
  d: path("M14.1 12.78a.88.88 0 1 0 0-1.76a.88.88 0 0 0 0 1.76");
}

.ksafu5i5r {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m6.969 12.89l-1.64.376");
}

.kunikvhbc {
  stop-color: var(--svg-color--b79c31, #B79C31);
  stop-opacity: 0;
}

.l2nnv6ofr {
  stop-color: var(--svg-color--ec7931, #EC7931);
}

.l87ek2beb {
  stop-color: var(--svg-color--d27040, #D27040);
}

.mjmd3uius {
  d: path("M13.88 29.84v-8.19c-1.56.6-3.65-.16-3.76-2.36c-.01-.1-.01-.2-.01-.31V6.2c0-.138-.112-.252-.25-.236c-1.123.124-2 1.08-2 2.236v4.44c0 .17-.14.31-.31.31s-.31-.14-.31-.31V8.2a2.24 2.24 0 0 0-1.99-2.236C5.112 5.948 5 6.062 5 6.2v12.68c0 7.21 3.99 10.43 9.23 11c-.11-.01-.23-.02-.35-.04");
}

.ng50o3b4p {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m8.063 12.89l1.546.344");
}

.npbte4blh {
  d: path("M18.59 2.95a7.08 7.08 0 0 0-7.08 7.08v1.1a5.97 5.97 0 0 0 2.81 5.07c.79.49 1.25 1.37 1.25 2.3v.63c0 1.32-.74 2.17-1.68 2.53v8.2c.67.09 1.37.13 2.08.14c6.07.02 11.02-4.92 11.02-10.99v-7.66c-.01-4.64-3.77-8.4-8.4-8.4");
}

.nq57subgg {
  stop-color: var(--svg-color--ffa53a, #FFA53A);
}

.nvwsbdn3q {
  stop-color: var(--svg-color--c26b57, #C26B57);
}

.nyeg3ej3p {
  stop-color: var(--svg-color--f38d2b, #F38D2B);
  stop-opacity: 0;
}

.oodbhcj6a {
  stop-color: var(--svg-color--ff986d, #FF986D);
  stop-opacity: 0;
}

.p475_abra {
  stop-color: var(--svg-color--ff2c00, #FF2C00);
}

.pd9gmgghz {
  stop-color: var(--svg-color--f79e52, #F79E52);
  stop-opacity: 0;
}

.pkfzjdbgk {
  stop-color: var(--svg-color--c76057, #C76057);
}

.pom_j7bfz {
  stop-color: var(--svg-color--d67d35, #D67D35);
  stop-opacity: 0;
}

.quslypbnc {
  d: path("M17.79 13.26a1.12 1.12 0 1 0 0-2.24a1.12 1.12 0 0 0 0 2.24");
}

.qysx3lb4z {
  stop-color: var(--svg-color--ff9742, #FF9742);
}

.rvbr40bnw {
  stop-color: var(--svg-color--fd7535, #FD7535);
}

.s06g_9bfd {
  stop-color: var(--svg-color--ff5c1e, #FF5C1E);
}

.sh1u5ab0i {
  stop-color: var(--svg-color--ffb535, #FFB535);
}

.sys2tebvs {
  stop-color: var(--svg-color--baa332, #BAA332);
}

.t-di_ibdb {
  stop-color: var(--svg-color--ff9b6f, #FF9B6F);
}

.tv-do7hac {
  stop-color: var(--svg-color--ffa36a, #FFA36A);
}

.twrhtrbad {
  stop-color: var(--svg-color--c16959, #C16959);
  stop-opacity: 0;
}

.v1rov3uzm {
  stop-color: var(--svg-color--ffa972, #FFA972);
  stop-opacity: 0;
}

.w7dwk1bxr {
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("m6.969 12.89l-1.633.172");
}

.xdhgtcb5f {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M5.281 6.188c.354.046 1.163.35 1.563 1.187");
}

.xmcx18bah {
  stop-color: var(--svg-color--e16a28, #E16A28);
}

.y2wtsnj4m {
  stop-color: var(--svg-color--ff8028, #FF8028);
}

.yor3y3bqw {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M9.953 6.188c-.354.046-1.162.35-1.562 1.187");
}

.zcklf9bhv {
  fill: var(--svg-color--d1344c, #D1344C);
  d: path("M13.88 29.84v-8.19c-1.56.6-3.65-.16-3.76-2.36c-.01-.1-.01-.2-.01-.31V6.2c0-.138-.112-.252-.25-.236c-1.123.124-2 1.08-2 2.236v4.44c0 .17-.14.31-.31.31s-.31-.14-.31-.31V8.2a2.24 2.24 0 0 0-1.99-2.236C5.112 5.948 5 6.062 5 6.2v12.68c0 7.21 3.99 10.43 9.23 11c-.11-.01-.23-.02-.35-.04");
}

.zjwaehbsp {
  stop-color: var(--svg-color--ffd437, #FFD437);
}

</style>
