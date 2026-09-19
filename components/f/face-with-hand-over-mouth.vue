<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><g filter="url(#iPcjZob)"><circle fill="url(#imvW1Sb)" class="f-ark0b5m"/></g><circle fill="url(#iOyXFvd)" class="jn-i47blq"/><circle fill="url(#iE21S4c)" class="sfw-yhb6h"/><g filter="url(#irXvCCb)"><path stroke="url(#iNwvVfc)" class="eevxwkz5y"/></g><g filter="url(#ieG3Ooe)"><path stroke="url(#iQktUfb)" class="v305o1bya"/></g><path stroke="url(#ia8zA6d)" class="m1wrsqbtl"/><path stroke="url(#iS4cPld)" class="dq90cxogp"/><g filter="url(#iOrpRhj)"><path fill="url(#i4CF5nc)" class="un43alb-t"/><path fill="url(#iOamHsc)" class="un43alb-t"/><path fill="url(#ip9YZox)" class="un43alb-t"/></g><path fill="url(#iJjtMle)" class="mrbwvyb7i"/><path fill="url(#iseW3Xb)" class="f0bq-obdm"/><path fill="url(#iTNVHQc)" class="jhggcybsq"/><path fill="url(#iSeMPgi)" class="z0qgt-9ep"/><path fill="url(#i8kBK2c)" class="clh0whu8u"/><g filter="url(#iO9ELBb)"><path fill="url(#i6O8V0b)" class="gf0a1nbto"/></g><g filter="url(#iTLexTd)"><path fill="url(#izuWbNc)" class="vieoq1ysk"/></g><g filter="url(#ilPGP4b)"><path fill="url(#iyN8yvc)" class="f9recd5eo"/></g><g filter="url(#iaZz9qd)"><path fill="url(#iuGeZFe)" class="nauq9nb3p"/></g><g filter="url(#i1771xb)"><path stroke="url(#i2tFrlX)" class="if9ri3w4y"/></g><path fill="url(#iYviPWb)" class="x05cc_bsw"/><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="imvW1Sb" cx="0" cy="0" r="1" gradientTransform="matrix(3.21875 -4.5625 4.91078 3.46445 10.216 19.969)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="w80dwybjd"/><stop offset="1" class="z016bf25m"/></radialGradient><radialGradient id="iOyXFvd" cx="0" cy="0" r="1" gradientTransform="rotate(89.995 5.524 20.475)scale(3.92207)" gradientUnits="userSpaceOnUse"><stop class="mjqiqzbqp"/><stop offset="1" class="og2_-db3e"/></radialGradient><radialGradient id="iE21S4c" cx="0" cy="0" r="1" gradientTransform="rotate(89.995 -4.475 10.475)scale(3.92207)" gradientUnits="userSpaceOnUse"><stop class="qid5qyb1f"/><stop offset="1" class="og2_-db3e"/></radialGradient><radialGradient id="iNwvVfc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09376 3 -5.38561 -3.75873 22.5 11.063)" gradientUnits="userSpaceOnUse"><stop class="e58ypubby"/><stop offset=".634" class="kpj5w9bmw"/></radialGradient><radialGradient id="iQktUfb" cx="0" cy="0" r="1" gradientTransform="rotate(124.912 3.053 8.628)scale(3.65839 6.56756)" gradientUnits="userSpaceOnUse"><stop class="e58ypubby"/><stop offset=".634" class="kpj5w9bmw"/></radialGradient><radialGradient id="ia8zA6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.1875 -7.96875 9.82492 -.23118 10.5 12.188)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="ccr58nbuz"/><stop offset=".276" class="gvfj_gdms"/><stop offset=".401" class="ovz69fb_x"/></radialGradient><radialGradient id="iS4cPld" cx="0" cy="0" r="1" gradientTransform="matrix(-.1875 -7.96875 9.82492 -.23118 21.5 12.188)" gradientUnits="userSpaceOnUse"><stop offset=".167" class="ccr58nbuz"/><stop offset=".276" class="gvfj_gdms"/><stop offset=".401" class="ovz69fb_x"/></radialGradient><radialGradient id="i4CF5nc" cx="0" cy="0" r="1" gradientTransform="rotate(132.147 7.61 12.145)scale(32.3525 32.1482)" gradientUnits="userSpaceOnUse"><stop offset=".24" class="fgh-vhavg"/><stop offset=".614" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ip9YZox" cx="0" cy="0" r="1" gradientTransform="rotate(110.989 4.784 14.762)scale(20.6714 28.2125)" gradientUnits="userSpaceOnUse"><stop offset=".732" class="glgshpbvw"/><stop offset="1" class="iedbks3oi"/></radialGradient><radialGradient id="i6O8V0b" cx="0" cy="0" r="1" gradientTransform="matrix(-.8058 -.09436 .11026 -.94159 19.674 23.372)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="xus32fblm"/><stop offset=".724" class="ocwji7vfg"/></radialGradient><radialGradient id="izuWbNc" cx="0" cy="0" r="1" gradientTransform="matrix(-.8058 -.09436 .11026 -.94159 19.227 20.608)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="xus32fblm"/><stop offset=".724" class="ocwji7vfg"/></radialGradient><radialGradient id="iyN8yvc" cx="0" cy="0" r="1" gradientTransform="matrix(-.8058 -.09436 .11026 -.94159 18.32 18.175)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="xus32fblm"/><stop offset=".724" class="ocwji7vfg"/></radialGradient><radialGradient id="iuGeZFe" cx="0" cy="0" r="1" gradientTransform="matrix(-.8058 -.09436 .11026 -.94159 15.787 17.185)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="xus32fblm"/><stop offset=".724" class="ocwji7vfg"/></radialGradient><radialGradient id="iYviPWb" cx="0" cy="0" r="1" gradientTransform="rotate(142.226 2.263 10.792)scale(1.91039 2.0065)" gradientUnits="userSpaceOnUse"><stop offset=".328" class="url071kgq"/><stop offset=".724" class="ocwji7vfg"/></radialGradient><filter id="iPcjZob" width="12.25" height="12.25" x="7.684" y="15.219" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6806_5260" stdDeviation=".5"/></filter><filter id="irXvCCb" width="7.375" height="5.377" x="17.437" y="8.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6806_5260" stdDeviation=".25"/></filter><filter id="ieG3Ooe" width="7.375" height="5.377" x="6.812" y="8.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6806_5260" stdDeviation=".25"/></filter><filter id="iOrpRhj" width="15.453" height="16.091" x="7.047" y="14.074" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2" dy="-2"/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.08 0"/><feBlend in2="shape" result="effect1_innerShadow_6806_5260"/></filter><filter id="iO9ELBb" width="2.328" height="2.542" x="18.697" y="21.951" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6806_5260" stdDeviation=".25"/></filter><filter id="iTLexTd" width="2.328" height="2.542" x="18.25" y="19.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6806_5260" stdDeviation=".25"/></filter><filter id="ilPGP4b" width="2.328" height="2.542" x="17.341" y="16.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6806_5260" stdDeviation=".25"/></filter><filter id="iaZz9qd" width="2.328" height="2.542" x="14.81" y="15.765" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6806_5260" stdDeviation=".25"/></filter><filter id="i1771xb" width="8.125" height="9.157" x="10.188" y="18.726" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6806_5260" stdDeviation=".75"/></filter><linearGradient id="iOamHsc" x1="3.686" x2="8.828" y1="17.979" y2="17.419" gradientUnits="userSpaceOnUse"><stop offset=".328" class="zus2g1bwj"/><stop offset=".865" class="z016bf25m"/></linearGradient><linearGradient id="iJjtMle" x1="10.937" x2="13.75" y1="15.383" y2="18.289" gradientUnits="userSpaceOnUse"><stop offset=".386" class="t56wa9uix"/><stop offset=".545" class="xw7_k5baw"/><stop offset="1" class="z016bf25m"/></linearGradient><linearGradient id="iseW3Xb" x1="14.188" x2="15.254" y1="18.602" y2="19.718" gradientUnits="userSpaceOnUse"><stop offset=".386" class="t56wa9uix"/><stop offset=".545" class="xw7_k5baw"/><stop offset="1" class="z016bf25m"/></linearGradient><linearGradient id="iTNVHQc" x1="15.75" x2="16.991" y1="20.039" y2="21.377" gradientUnits="userSpaceOnUse"><stop offset=".386" class="t56wa9uix"/><stop offset=".545" class="xw7_k5baw"/><stop offset="1" class="z016bf25m"/></linearGradient><linearGradient id="iSeMPgi" x1="17.656" x2="18.669" y1="22.067" y2="23.156" gradientUnits="userSpaceOnUse"><stop offset=".386" class="t56wa9uix"/><stop offset=".545" class="xw7_k5baw"/><stop offset="1" class="z016bf25m"/></linearGradient><linearGradient id="i8kBK2c" x1="10.157" x2="9.555" y1="21.656" y2="21.338" gradientUnits="userSpaceOnUse"><stop offset=".307" class="we9tu7l_e"/><stop offset="1" class="z016bf25m"/></linearGradient><linearGradient id="i2tFrlX" x1="10.921" x2="17.254" y1="20.977" y2="27.71" gradientUnits="userSpaceOnUse"><stop offset=".328" class="q0n-e9fcm"/><stop offset="1" class="ocwji7vfg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:face-with-hand-over-mouth" /></template>
<style>
.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.ccr58nbuz {
  stop-color: var(--svg-color--482641, #482641);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.clh0whu8u {
  d: path("m8.934 22.438l2.246-2.782c.415-1.562-.023-1.925-.128-2.086z");
}

.dq90cxogp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 12s.5-2 2.5-2s2.5 2 2.5 2");
}

.e58ypubby {
  stop-color: var(--svg-color--ca7a1b, #CA7A1B);
}

.eevxwkz5y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.938 11.656s.617-1.522 2.187-1.25c2.035.352 2.188 2.344 2.188 2.344");
}

.f-ark0b5m {
  cx: 13.809px;
  cy: 21.344px;
  r: 5.125px;
}

.f0bq-obdm {
  d: path("M13.366 21.3a1.31 1.31 0 0 0 .29 1.55a1.42 1.42 0 0 0 1.962-.052l3.365-3.572c.53-.54.513-1.39-.04-1.902a1.42 1.42 0 0 0-1.96.052l-.486.515c-.094.093-.253.282-.356.386z");
}

.f9recd5eo {
  d: path("M18.843 18.748c-.315.148-.723-.056-.91-.455c-.186-.4-.082-.842.234-.99c.315-.148.723.056.91.455c.186.4.082.843-.234.99");
}

.fgh-vhavg {
  stop-color: var(--svg-color--ffd43c, #FFD43C);
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft5dv1b6b {
  fill: none;
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.gf0a1nbto {
  d: path("M20.2 23.945c-.316.147-.723-.057-.91-.456s-.082-.842.233-.99c.316-.148.723.056.91.455c.187.4.082.843-.233.99");
}

.glgshpbvw {
  stop-color: var(--svg-color--fd61c2, #FD61C2);
  stop-opacity: 0;
}

.gvfj_gdms {
  stop-color: var(--svg-color--503a4a, #503A4A);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.iedbks3oi {
  stop-color: var(--svg-color--ff63c4, #FF63C4);
}

.if9ri3w4y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.438 20.977c.99.625 3.1 2.43 3.624 4.656");
}

.jhggcybsq {
  d: path("M14.776 23.088c.04.29.36.7.594.917c.553.51 1.43.488 1.961-.052l2.27-2.308c.531-.54.651-1.4.099-1.91a1.8 1.8 0 0 0-.412-.265c-.396-.194-.839-.033-1.151.277z");
}

.jn-i47blq {
  cx: 25.998px;
  cy: 14.76px;
  r: 4px;
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.kpj5w9bmw {
  stop-color: var(--svg-color--ca7a1b, #CA7A1B);
  stop-opacity: 0;
}

.m1wrsqbtl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 12s.25-2 2.5-2s2.5 2 2.5 2");
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mjqiqzbqp {
  stop-color: var(--svg-color--ff63c4, #FF63C4);
  stop-opacity: 0.5;
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.mrbwvyb7i {
  d: path("M14.306 16.484a1.364 1.364 0 0 1 1.887-.046c.525.486.552 1.291.06 1.81l-4.193 4.434c-.473.5-1.267.548-1.799.11l-.418-.345a.696.696 0 0 1-.096-.986l1.367-1.727z");
}

.nauq9nb3p {
  d: path("M16.312 17.758c-.316.148-.723-.056-.91-.455c-.186-.4-.082-.843.234-.99c.315-.148.722.056.91.455c.186.4.082.842-.234.99");
}

.ocwji7vfg {
  stop-color: var(--svg-color--fff478, #FFF478);
  stop-opacity: 0;
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.ovz69fb_x {
  stop-color: var(--svg-color--483637, #483637);
}

.q0n-e9fcm {
  stop-color: var(--svg-color--fff478, #FFF478);
  stop-opacity: 0.5;
}

.qid5qyb1f {
  stop-color: var(--svg-color--e840a8, #E840A8);
  stop-opacity: 0.5;
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.sfw-yhb6h {
  cx: 6px;
  cy: 14.76px;
  r: 4px;
}

.t56wa9uix {
  stop-color: var(--svg-color--83480a, #83480A);
}

.un43alb-t {
  d: path("M16.207 16.427a1.355 1.355 0 0 0-1.874.049l-3.167 3.22l.18-1.052c.125-.73-.383-1.415-1.134-1.531c-.755-.117-1.468.386-1.588 1.12l-.486 2.974l-.725 2.394a2 2 0 0 0-.034.133a4.65 4.65 0 0 0-.303 2.248c.287 2.584 2.635 4.444 5.244 4.154a4.76 4.76 0 0 0 2.899-1.416l4.835-4.329a1.304 1.304 0 0 0 .066-1.901a1.37 1.37 0 0 0-.839-.399l.454-.461c.53-.54.513-1.39-.04-1.902a1.4 1.4 0 0 0-.828-.363l.14-.142c.53-.54.512-1.39-.04-1.901a1.42 1.42 0 0 0-1.961.051l-.518.526a1.25 1.25 0 0 0-.281-1.472");
}

.url071kgq {
  stop-color: var(--svg-color--fff478, #FFF478);
  stop-opacity: 0.3;
}

.v305o1bya {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.313 11.656s.617-1.522 2.187-1.25c2.035.352 2.188 2.344 2.188 2.344");
}

.vieoq1ysk {
  d: path("M19.753 21.182c-.316.148-.723-.056-.91-.455c-.186-.4-.082-.843.233-.99c.316-.148.723.056.91.455s.082.842-.233.99");
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.w80dwybjd {
  stop-color: var(--svg-color--c16a0e, #C16A0E);
  stop-opacity: 0.53;
}

.we9tu7l_e {
  stop-color: var(--svg-color--e27f17, #E27F17);
  stop-opacity: 0.53;
}

.x05cc_bsw {
  d: path("M11.204 18.797c-.295.543-1.018.735-1.642.42c-.624-.316-.892-1.012-.597-1.555c.294-.543 1.04-.728 1.663-.413c.625.316.87 1.005.576 1.548");
}

.xus32fblm {
  stop-color: var(--svg-color--faf194, #FAF194);
  stop-opacity: 0.4;
}

.xw7_k5baw {
  stop-color: var(--svg-color--cd7313, #CD7313);
}

.z016bf25m {
  stop-color: var(--svg-color--fa9428, #FA9428);
  stop-opacity: 0;
}

.z0qgt-9ep {
  d: path("m16.544 24.688l1.36 1.609l1.374-1.219l.74-.682a1.314 1.314 0 0 0 .063-1.92a1.4 1.4 0 0 0-.454-.304c-.267-.111-.559.012-.764.216z");
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

.zus2g1bwj {
  stop-color: var(--svg-color--ee891e, #EE891E);
}

</style>
