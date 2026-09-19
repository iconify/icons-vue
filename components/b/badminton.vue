<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i3B5z9I)" class="l0p2ty5du"/><path fill="url(#iWQtLNb)" class="l0p2ty5du"/><g filter="url(#iM4pGle)"><path class="nalzfbboz"/></g><path stroke="url(#iky0cve)" class="mxh07fm0x"/><path stroke="url(#iaM57Uc)" class="xd2q8qofa"/><path stroke="url(#ivduVoe)" class="ij1nlzrgq"/><path class="a1yje-b1j"/><path stroke="url(#iowhOhe)" class="pu12c7blm"/><path stroke="url(#iEFmvGz)" class="pu12c7blm"/><path stroke="url(#iY5gzke)" class="pu12c7blm"/><path stroke="url(#imJp8Ta)" class="pu12c7blm"/><path class="bzyx3acgx"/><path stroke="url(#i0xAuIb)" class="z4tp66b_l"/><path stroke="url(#iBbUv2d)" class="z4tp66b_l"/><path stroke="url(#iWR6cdb)" class="z4tp66b_l"/><path stroke="url(#iJmSjid)" class="z4tp66b_l"/><path class="nkqflobux"/><path stroke="url(#iNMjhne)" class="t_mcm3uih"/><path stroke="url(#iCW14bz)" class="t_mcm3uih"/><path stroke="url(#iByBfBb)" class="t_mcm3uih"/><path stroke="url(#ia16FLm)" class="t_mcm3uih"/><path class="pqpac1jvv"/><path stroke="url(#ixO45cd)" class="nb6d_sb3q"/><path stroke="url(#iA6hLLb)" class="nb6d_sb3q"/><path stroke="url(#ir2GHAb)" class="nb6d_sb3q"/><path stroke="url(#iO47U3c)" class="nb6d_sb3q"/><g filter="url(#iIFBnTg)"><path stroke="url(#iBJyOfe)" class="z0mg7hbhv"/></g><path stroke="url(#iriIJNc)" class="z0mg7hbhv"/><g filter="url(#ibgrU9b)"><path stroke="url(#i0NIHEd)" class="uxxqv8bfz"/></g><g filter="url(#iDcdjHe)"><path class="ou3cb_3mb"/><path fill="url(#i7IJZsi)" class="i_k3-nb8g"/></g><path fill="url(#ivV2dPc)" class="i_k3-nb8g"/><path class="ffkfj4_po"/><path fill="url(#iTFngKd)" class="jrthbx-nj"/><path fill="url(#isrM4Yl)" class="jrthbx-nj"/><g filter="url(#iP1QBOc)"><path class="fdhjuyqot"/><path fill="url(#iWLo6Le)" class="ymhi9118a"/></g><path fill="url(#ibfI5hb)" class="ckndvxbhb"/><defs><linearGradient id="iky0cve" x1="14.839" x2="15.514" y1="7.841" y2="8.231" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iaM57Uc" x1="17.516" x2="18.19" y1="9.628" y2="10.018" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="ivduVoe" x1="20.402" x2="21.076" y1="11.053" y2="11.442" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="iowhOhe" x1="19.599" x2="19.828" y1="5.815" y2="5.422" gradientUnits="userSpaceOnUse"><stop class="ioywqwebb"/><stop offset="1" class="pzy4omb-s"/></linearGradient><linearGradient id="iEFmvGz" x1="20.375" x2="20.225" y1="5.227" y2="5.48" gradientUnits="userSpaceOnUse"><stop class="x0g8qbbwu"/><stop offset="1" class="au_p8zbbn"/></linearGradient><linearGradient id="i0xAuIb" x1="18.02" x2="18.269" y1="8.565" y2="8.138" gradientUnits="userSpaceOnUse"><stop class="ioywqwebb"/><stop offset="1" class="pzy4omb-s"/></linearGradient><linearGradient id="iBbUv2d" x1="18.862" x2="18.7" y1="7.925" y2="8.201" gradientUnits="userSpaceOnUse"><stop class="x0g8qbbwu"/><stop offset="1" class="au_p8zbbn"/></linearGradient><linearGradient id="iNMjhne" x1="16.45" x2="16.698" y1="11.29" y2="10.863" gradientUnits="userSpaceOnUse"><stop class="ioywqwebb"/><stop offset="1" class="pzy4omb-s"/></linearGradient><linearGradient id="iCW14bz" x1="17.292" x2="17.13" y1="10.651" y2="10.927" gradientUnits="userSpaceOnUse"><stop class="x0g8qbbwu"/><stop offset="1" class="au_p8zbbn"/></linearGradient><linearGradient id="ixO45cd" x1="14.884" x2="15.113" y1="13.98" y2="13.587" gradientUnits="userSpaceOnUse"><stop class="ioywqwebb"/><stop offset="1" class="pzy4omb-s"/></linearGradient><linearGradient id="iA6hLLb" x1="15.659" x2="15.51" y1="13.393" y2="13.646" gradientUnits="userSpaceOnUse"><stop class="x0g8qbbwu"/><stop offset="1" class="au_p8zbbn"/></linearGradient><linearGradient id="iBJyOfe" x1="22.25" x2="14.312" y1="2.875" y2="17.534" gradientUnits="userSpaceOnUse"><stop class="u1aeue75w"/><stop offset="1" class="nwy_nxb_g"/></linearGradient><linearGradient id="i0NIHEd" x1="22.375" x2="14.843" y1="3.188" y2="17" gradientUnits="userSpaceOnUse"><stop class="xzw6u_rdx"/><stop offset=".189" class="gv7b8nmnj"/><stop offset=".806" class="rpxdnxboe"/><stop offset="1" class="tc1v_acal"/></linearGradient><linearGradient id="i7IJZsi" x1="16.745" x2="18.376" y1="22.72" y2="22.949" gradientUnits="userSpaceOnUse"><stop class="qs7lvbbhq"/><stop offset="1" class="q6nw6osac"/></linearGradient><linearGradient id="ivV2dPc" x1="20.128" x2="20.435" y1="24.546" y2="23.316" gradientUnits="userSpaceOnUse"><stop offset=".236" class="b25ho2-gc"/><stop offset="1" class="gtd6cabgj"/></linearGradient><linearGradient id="iTFngKd" x1="17.744" x2="17.629" y1="24.565" y2="26.756" gradientUnits="userSpaceOnUse"><stop class="bb431oowl"/><stop offset="1" class="n0j6pibnu"/></linearGradient><linearGradient id="iWLo6Le" x1="16.86" x2="18.09" y1="23.738" y2="23.969" gradientUnits="userSpaceOnUse"><stop class="qs7lvbbhq"/><stop offset="1" class="q6nw6osac"/></linearGradient><radialGradient id="i3B5z9I" cx="0" cy="0" r="1" gradientTransform="rotate(118.955 1.027 13.365)scale(8.71427 2.00175)" gradientUnits="userSpaceOnUse"><stop offset=".187" class="i-ql02m7h"/><stop offset="1" class="vu9tnbb3z"/></radialGradient><radialGradient id="iWQtLNb" cx="0" cy="0" r="1" gradientTransform="matrix(3.35264 -5.77448 4.48448 2.60368 10.49 22.774)" gradientUnits="userSpaceOnUse"><stop offset=".777" class="lwtead3ud"/><stop offset=".94" class="kai4vkzbr"/></radialGradient><radialGradient id="iY5gzke" cx="0" cy="0" r="1" gradientTransform="matrix(-.89062 .29688 -.89688 -2.69063 24.671 7.516)" gradientUnits="userSpaceOnUse"><stop offset=".326" class="lj_0dac2p"/><stop offset="1" class="l4jxbwd6m"/></radialGradient><radialGradient id="imJp8Ta" cx="0" cy="0" r="1" gradientTransform="matrix(.15625 .75687 -3.0339 .62633 16.343 3.04)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="ow5o_ac6r"/><stop offset="1" class="ah1-c4bze"/></radialGradient><radialGradient id="iWR6cdb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5 .40625 -1.22767 -4.53295 24.593 10.531)" gradientUnits="userSpaceOnUse"><stop offset=".326" class="lj_0dac2p"/><stop offset="1" class="l4jxbwd6m"/></radialGradient><radialGradient id="iJmSjid" cx="0" cy="0" r="1" gradientTransform="matrix(.53125 .73749 -2.9552 2.12878 13.75 4.813)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="ow5o_ac6r"/><stop offset="1" class="ah1-c4bze"/></radialGradient><radialGradient id="iByBfBb" cx="0" cy="0" r="1" gradientTransform="rotate(164.87 10.632 8.155)scale(1.55386 4.68884)" gradientUnits="userSpaceOnUse"><stop offset=".326" class="lj_0dac2p"/><stop offset="1" class="l4jxbwd6m"/></radialGradient><radialGradient id="ia16FLm" cx="0" cy="0" r="1" gradientTransform="rotate(54.187 -1.283 15.676)scale(.9079 3.63997)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="ow5o_ac6r"/><stop offset="1" class="ah1-c4bze"/></radialGradient><radialGradient id="ir2GHAb" cx="0" cy="0" r="1" gradientTransform="matrix(-.4375 -1.28125 3.86804 -1.32078 19.968 17.156)" gradientUnits="userSpaceOnUse"><stop offset=".326" class="lj_0dac2p"/><stop offset="1" class="l4jxbwd6m"/></radialGradient><radialGradient id="iO47U3c" cx="0" cy="0" r="1" gradientTransform="matrix(.48867 .67759 -2.71617 1.95886 10.956 10.532)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="ow5o_ac6r"/><stop offset="1" class="ah1-c4bze"/></radialGradient><radialGradient id="iriIJNc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.06263 13.31508 -11.54004 -6.9878 21.593 4.219)" gradientUnits="userSpaceOnUse"><stop offset=".852" class="nm8lq_b0v"/><stop offset=".982" class="iuci67bre"/></radialGradient><radialGradient id="isrM4Yl" cx="0" cy="0" r="1" gradientTransform="rotate(15.934 -84.16 71.794)scale(3.67794 2.25139)" gradientUnits="userSpaceOnUse"><stop offset=".799" class="p-btsx1rl"/><stop offset="1" class="rkqoc588a"/></radialGradient><radialGradient id="ibfI5hb" cx="0" cy="0" r="1" gradientTransform="rotate(120.738 2.322 16.169)scale(2.93479 3.02351)" gradientUnits="userSpaceOnUse"><stop class="e8nxx7boq"/><stop offset="1" class="v69zfy0ry"/></radialGradient><filter id="iM4pGle" width="5.926" height="7.086" x="6" y="22.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.180392 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2616"/></filter><filter id="iIFBnTg" width="15.921" height="16.887" x="10.071" y="1.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.545098 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2616"/></filter><filter id="ibgrU9b" width="15.387" height="16.283" x="10.276" y="1.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_2616" stdDeviation=".2"/></filter><filter id="iDcdjHe" width="4.38" height="2.448" x="17.245" y="21.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.956863 0 0 0 0 0.980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2616"/></filter><filter id="iP1QBOc" width="4.654" height="3.565" x="16.19" y="22.466" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.576471 0 0 0 0 0.788235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_2616"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.956863 0 0 0 0 0.980392 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_2616" result="effect2_innerShadow_18_2616"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:badminton" /></template>
<style>
.a1yje-b1j {
  stroke: var(--svg-color--dddfe9, #DDDFE9);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-674px, 0.674px);
  d: path("m15.515 3.04l9.42 5.44");
}

.ah1-c4bze {
  stop-color: var(--svg-color--a8b1cc, #A8B1CC);
  stop-opacity: 0;
}

.au_p8zbbn {
  stop-color: var(--svg-color--acb3c2, #ACB3C2);
  stop-opacity: 0;
}

.b25ho2-gc {
  stop-color: var(--svg-color--d3c8dd, #D3C8DD);
}

.bb431oowl {
  stop-color: var(--svg-color--af85ba, #AF85BA);
}

.bzyx3acgx {
  stroke: var(--svg-color--dddfe9, #DDDFE9);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-674px, 0.674px);
  d: path("m13.585 5.55l10.23 5.91");
}

.ckndvxbhb {
  d: path("M15.025 22.35a1.72 1.72 0 0 1 2.34-.66l.51.28l-1.68 2.99l-.51-.28a1.71 1.71 0 0 1-.66-2.33");
}

.e8nxx7boq {
  stop-color: var(--svg-color--ff4688, #FF4688);
}

.fdhjuyqot {
  fill: var(--svg-color--d7cadf, #D7CADF);
  d: path("M20.635 25.5c.23-.41.08-.92-.32-1.15l-3.195-1.784l-.83 1.48l3.195 1.784c.41.22.92.07 1.15-.33");
}

.ffkfj4_po {
  fill: var(--svg-color--bea5d2, #BEA5D2);
  d: path("M19.765 27.05a.932.932 0 0 1-1.5.17l-2.08-2.26l.42-.76l2.79 1.57c.46.26.62.83.37 1.28");
}

.ft5dv1b6b {
  fill: none;
}

.gtd6cabgj {
  stop-color: var(--svg-color--d3c8dd, #D3C8DD);
  stop-opacity: 0;
}

.gv7b8nmnj {
  stop-color: var(--svg-color--41bff9, #41BFF9);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.i_k3-nb8g {
  d: path("M21.505 23.94a.932.932 0 0 0-.63-1.37l-3.01-.6l-.42.76l2.79 1.57c.45.25 1.02.09 1.27-.36");
}

.i-ql02m7h {
  stop-color: var(--svg-color--367fdf, #367FDF);
}

.ij1nlzrgq {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-674px, 0.674px);
  d: path("m24.315 5.21l-7.14 12.15");
}

.ioywqwebb {
  stop-color: var(--svg-color--b29ec6, #B29EC6);
}

.iuci67bre {
  stop-color: var(--svg-color--282eba, #282EBA);
}

.jrthbx-nj {
  d: path("M19.765 27.05a.932.932 0 0 1-1.5.17l-2.08-2.26l.42-.76l2.79 1.57c.46.26.62.83.37 1.28");
}

.kai4vkzbr {
  stop-color: var(--svg-color--2653c1, #2653C1);
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.l0p2ty5du {
  d: path("M6.615 29.32c-.58-.34-.78-1.08-.45-1.67l6.69-11.58l2.12 1.22l-6.69 11.58c-.34.58-1.09.78-1.67.45");
}

.l4jxbwd6m {
  stop-color: var(--svg-color--868fa9, #868FA9);
  stop-opacity: 0;
}

.lj_0dac2p {
  stop-color: var(--svg-color--868fa9, #868FA9);
}

.lwtead3ud {
  stop-color: var(--svg-color--2653c1, #2653C1);
  stop-opacity: 0;
}

.mxh07fm0x {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-674px, 0.674px);
  d: path("m18.745 2l-7.13 12.14");
}

.n0j6pibnu {
  stop-color: var(--svg-color--af85ba, #AF85BA);
  stop-opacity: 0;
}

.nalzfbboz {
  fill: var(--svg-color--593f6c, #593F6C);
  d: path("m9.055 22.65l-2.89 5c-.34.58-.14 1.33.45 1.67c.58.34 1.33.14 1.67-.45l2.89-5z");
}

.nb6d_sb3q {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-674px, 0.674px);
  d: path("m10.805 11.21l9.41 5.43");
}

.nkqflobux {
  stroke: var(--svg-color--dddfe9, #DDDFE9);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-674px, 0.674px);
  d: path("m12.015 8.28l10.23 5.9");
}

.nm8lq_b0v {
  stop-color: var(--svg-color--282eba, #282EBA);
  stop-opacity: 0;
}

.nwy_nxb_g {
  stop-color: var(--svg-color--3346b4, #3346B4);
}

.ou3cb_3mb {
  fill: var(--svg-color--ded7e0, #DED7E0);
  d: path("M21.505 23.94a.932.932 0 0 0-.63-1.37l-3.01-.6l-.42.76l2.79 1.57c.45.25 1.02.09 1.27-.36");
}

.ow5o_ac6r {
  stop-color: var(--svg-color--a8b1cc, #A8B1CC);
}

.p-btsx1rl {
  stop-color: var(--svg-color--d1bfe1, #D1BFE1);
  stop-opacity: 0;
}

.pqpac1jvv {
  stroke: var(--svg-color--dddfe9, #DDDFE9);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-674px, 0.674px);
  d: path("m10.805 11.21l9.41 5.43");
}

.pu12c7blm {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-674px, 0.674px);
  d: path("m15.515 3.04l9.42 5.44");
}

.pzy4omb-s {
  stop-color: var(--svg-color--b29ec6, #B29EC6);
  stop-opacity: 0;
}

.q6nw6osac {
  stop-color: var(--svg-color--eabbd6, #EABBD6);
  stop-opacity: 0;
}

.qs7lvbbhq {
  stop-color: var(--svg-color--eabbd6, #EABBD6);
}

.rkqoc588a {
  stop-color: var(--svg-color--d1bfe1, #D1BFE1);
}

.rpxdnxboe {
  stop-color: var(--svg-color--5878df, #5878DF);
  stop-opacity: 0;
}

.t_mcm3uih {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-674px, 0.674px);
  d: path("m12.015 8.28l10.23 5.9");
}

.tc1v_acal {
  stop-color: var(--svg-color--5878df, #5878DF);
}

.u1aeue75w {
  stop-color: var(--svg-color--27b5ed, #27B5ED);
}

.uxxqv8bfz {
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M21.856 3.08a6.524 6.524 0 0 0-8.91 2.39L11.7 7.605a6.524 6.524 0 0 0 11.3 6.52l1.245-2.135c1.79-3.12.72-7.11-2.39-8.91Z");
}

.v69zfy0ry {
  stop-color: var(--svg-color--b33982, #B33982);
}

.vu9tnbb3z {
  stop-color: var(--svg-color--4161ad, #4161AD);
}

.x0g8qbbwu {
  stop-color: var(--svg-color--acb3c2, #ACB3C2);
}

.xd2q8qofa {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-674px, 0.674px);
  d: path("m21.525 3.6l-7.34 12.51");
}

.xzw6u_rdx {
  stop-color: var(--svg-color--41bff9, #41BFF9);
}

.ymhi9118a {
  d: path("M20.635 25.5c.23-.41.08-.92-.32-1.15l-3.195-1.784l-.83 1.48l3.195 1.784c.41.22.92.07 1.15-.33");
}

.z0mg7hbhv {
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-36px, 1.36px);
  d: path("M21.855 3.08a6.524 6.524 0 0 0-8.91 2.39l-1.32 2.28a6.524 6.524 0 0 0 11.3 6.52l1.32-2.28c1.79-3.12.72-7.11-2.39-8.91Z");
}

.z4tp66b_l {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-674px, 0.674px);
  d: path("m13.585 5.55l10.23 5.91");
}

</style>
