<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#inyK1lm)"><path fill="url(#icM417d)" class="c9cnarajy"/><path fill="url(#i6WcvLn)" class="c9cnarajy"/></g><path fill="url(#iv4Gd8c)" class="c9cnarajy"/><path fill="url(#iJsIvUb)" class="c9cnarajy"/><path fill="url(#iqxkqQe)" class="c9cnarajy"/><path fill="url(#iR7BZYd)" class="c9cnarajy"/><path fill="url(#iwVXvVb)" class="c9cnarajy"/><g filter="url(#ibn5exb)"><path clip-rule="evenodd" class="rsj74xbic"/></g><g filter="url(#iOrQl7b)"><path stroke="url(#iDGmIwd)" class="u9c8p6q2e"/></g><g filter="url(#iQ1K6Ac)"><path class="j5c3bwmeq"/></g><g filter="url(#iT5ozqd)"><path stroke="url(#iS7mptd)" class="mo5o3wbvd"/></g><g filter="url(#iCHdbtc)"><path stroke="url(#iFMUTGe)" class="o8vq4_ixs"/></g><g filter="url(#irb3Ltd)"><path stroke="url(#i8XTpRd)" class="di0rlkb3k"/></g><path fill="url(#iT3tdgd)" class="sm1yccbtp"/><path fill="url(#iQrZFkP)" class="sm1yccbtp"/><path fill="url(#igO51he)" class="sm1yccbtp"/><path fill="url(#iwj9e9b)" class="sm1yccbtp"/><path fill="url(#iWnGGDe)" class="xv8a7ebxl"/><path fill="url(#iu4wk4T)" class="xv8a7ebxl"/><path fill="url(#iIdGnCe)" class="xv8a7ebxl"/><path fill="url(#i8lARDc)" class="xv8a7ebxl"/><path fill="url(#irrdRlY)" class="qmsogbc6q"/><path fill="url(#iYle53b)" class="qmsogbc6q"/><path fill="url(#ihxUb3b)" class="qmsogbc6q"/><path fill="url(#i29jg5b)" class="qmsogbc6q"/><path fill="url(#iGmcC5c)" class="maxp1bbvh"/><path fill="url(#iMqptOe)" class="maxp1bbvh"/><path fill="url(#i3pd7ne)" class="maxp1bbvh"/><path fill="url(#iLr7rNY)" class="maxp1bbvh"/><g filter="url(#izIzpIe)"><path class="fgfhc4b1p"/><path fill="url(#izIGy5b)" class="ltf3mccry"/><path fill="url(#i4A54ye)" class="ltf3mccry"/><path fill="url(#iOwbkKe)" class="ltf3mccry"/></g><path fill="url(#ivvcJke)" class="ltf3mccry"/><g filter="url(#iCkDrLe)"><path class="d0le1xg3b"/></g><defs><radialGradient id="i6WcvLn" cx="0" cy="0" r="1" gradientTransform="matrix(-2.56252 3.99998 -5.56204 -3.56323 19.963 10.47)" gradientUnits="userSpaceOnUse"><stop class="hns7l1blj"/><stop offset="1" class="h56ds_bxn"/></radialGradient><radialGradient id="iv4Gd8c" cx="0" cy="0" r="1" gradientTransform="matrix(-2 -1.90624 1.52119 -1.59601 26.4 24.157)" gradientUnits="userSpaceOnUse"><stop class="nbwql2bcw"/><stop offset="1" class="aubc5ccdr"/></radialGradient><radialGradient id="iJsIvUb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.53124 -3.09376 .84515 -.96466 27.057 22.97)" gradientUnits="userSpaceOnUse"><stop class="l7_-qjbkm"/><stop offset="1" class="ndohv0r2p"/></radialGradient><radialGradient id="iqxkqQe" cx="0" cy="0" r="1" gradientTransform="rotate(-134.193 17.942 8.348)scale(6.2762 1.71453)" gradientUnits="userSpaceOnUse"><stop class="l7_-qjbkm"/><stop offset="1" class="ndohv0r2p"/></radialGradient><radialGradient id="iR7BZYd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.40627 -3.53124 1.1197 -1.08007 20.088 28.876)" gradientUnits="userSpaceOnUse"><stop class="l7_-qjbkm"/><stop offset="1" class="ndohv0r2p"/></radialGradient><radialGradient id="iwVXvVb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.25002 -3.65624 1.07172 -1.24576 16.682 30.844)" gradientUnits="userSpaceOnUse"><stop class="l7_-qjbkm"/><stop offset="1" class="ndohv0r2p"/></radialGradient><radialGradient id="igO51he" cx="0" cy="0" r="1" gradientTransform="matrix(.0625 -3.1875 2.8824 .05652 5.276 22.813)" gradientUnits="userSpaceOnUse"><stop class="u-6tkfz7w"/><stop offset="1" class="ddr93pbtf"/></radialGradient><radialGradient id="iwj9e9b" cx="0" cy="0" r="1" gradientTransform="rotate(136.229 .953 9.928)scale(2.5749 2.49023)" gradientUnits="userSpaceOnUse"><stop class="d7lykbbcp"/><stop offset="1" class="qc1f41dre"/></radialGradient><radialGradient id="iIdGnCe" cx="0" cy="0" r="1" gradientTransform="matrix(.5 -4.12846 4.87877 .59087 7.557 25.844)" gradientUnits="userSpaceOnUse"><stop class="vhsap-b1a"/><stop offset="1" class="n212dmbbg"/></radialGradient><radialGradient id="i8lARDc" cx="0" cy="0" r="1" gradientTransform="rotate(136.026 1.78 11.877)scale(2.425 2.34528)" gradientUnits="userSpaceOnUse"><stop class="d7lykbbcp"/><stop offset="1" class="qc1f41dre"/></radialGradient><radialGradient id="ihxUb3b" cx="0" cy="0" r="1" gradientTransform="matrix(.375 -3.63103 4.2974 .44382 12.776 30.844)" gradientUnits="userSpaceOnUse"><stop class="vhsap-b1a"/><stop offset="1" class="n212dmbbg"/></radialGradient><radialGradient id="i29jg5b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.42361 1.37136 -1.3262 -1.37673 15.867 25.155)" gradientUnits="userSpaceOnUse"><stop class="d7lykbbcp"/><stop offset="1" class="qc1f41dre"/></radialGradient><radialGradient id="i3pd7ne" cx="0" cy="0" r="1" gradientTransform="rotate(-83.082 21.039 8.298)scale(3.78297 4.47857)" gradientUnits="userSpaceOnUse"><stop class="vhsap-b1a"/><stop offset="1" class="n212dmbbg"/></radialGradient><radialGradient id="iLr7rNY" cx="0" cy="0" r="1" gradientTransform="rotate(136.08 2.38 13.824)scale(2.20801 2.13528)" gradientUnits="userSpaceOnUse"><stop class="d7lykbbcp"/><stop offset="1" class="qc1f41dre"/></radialGradient><radialGradient id="izIGy5b" cx="0" cy="0" r="1" gradientTransform="matrix(10.09152 -6.72769 10.57376 15.86062 19.178 17.094)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="l_iu3xbdk"/><stop offset="1" class="rhhh3kv2j"/></radialGradient><radialGradient id="i4A54ye" cx="0" cy="0" r="1" gradientTransform="matrix(4.02295 -1.5768 2.532 6.46 10.95 10.735)" gradientUnits="userSpaceOnUse"><stop class="d8d8bfk5a"/><stop offset="1" class="gdgyw3b4h"/></radialGradient><radialGradient id="iOwbkKe" cx="0" cy="0" r="1" gradientTransform="matrix(6.72762 -5.36117 5.1162 6.42022 18.705 17.305)" gradientUnits="userSpaceOnUse"><stop class="fiuhwcb4z"/><stop offset="1" class="hzvcdyxra"/></radialGradient><radialGradient id="ivvcJke" cx="0" cy="0" r="1" gradientTransform="matrix(9.35565 -6.78022 10.60828 14.63776 20.229 15.518)" gradientUnits="userSpaceOnUse"><stop offset=".661" class="t6n1lgw1y"/><stop offset="1" class="fj0llis_o"/></radialGradient><linearGradient id="icM417d" x1="22.588" x2="15.901" y1="14.032" y2="23.844" gradientUnits="userSpaceOnUse"><stop class="m0lqw5bea"/><stop offset="1" class="j3nb6bcka"/></linearGradient><linearGradient id="iDGmIwd" x1="17.455" x2="13.825" y1="28.007" y2="24.445" gradientUnits="userSpaceOnUse"><stop class="bep7kfa5k"/><stop offset="1" class="ge_39wb5l"/></linearGradient><linearGradient id="iS7mptd" x1="26.682" x2="17.619" y1="20.045" y2="12.17" gradientUnits="userSpaceOnUse"><stop class="zaigj4bqx"/><stop offset="1" class="lb5l0hb7w"/></linearGradient><linearGradient id="iFMUTGe" x1="24.563" x2="20.932" y1="23.719" y2="20.157" gradientUnits="userSpaceOnUse"><stop class="ex4_2kakc"/><stop offset="1" class="bcgy66buw"/></linearGradient><linearGradient id="i8XTpRd" x1="21.309" x2="17.678" y1="26.289" y2="22.726" gradientUnits="userSpaceOnUse"><stop class="wyzm6k48s"/><stop offset="1" class="rp-_jcomq"/></linearGradient><linearGradient id="iT3tdgd" x1="7.682" x2="3.338" y1="17.157" y2="21.344" gradientUnits="userSpaceOnUse"><stop class="y35kqz9gt"/><stop offset="1" class="vwk_njbdz"/></linearGradient><linearGradient id="iQrZFkP" x1="7.291" x2="6.323" y1="21.173" y2="20.141" gradientUnits="userSpaceOnUse"><stop class="h-g_zlb9t"/><stop offset="1" class="fgvaegbje"/></linearGradient><linearGradient id="iWnGGDe" x1="10.713" x2="5.863" y1="19.685" y2="24.361" gradientUnits="userSpaceOnUse"><stop class="y35kqz9gt"/><stop offset="1" class="vwk_njbdz"/></linearGradient><linearGradient id="iu4wk4T" x1="10.277" x2="9.195" y1="24.17" y2="23.018" gradientUnits="userSpaceOnUse"><stop class="h-g_zlb9t"/><stop offset="1" class="fgvaegbje"/></linearGradient><linearGradient id="irrdRlY" x1="15.383" x2="11.432" y1="25.56" y2="29.373" gradientUnits="userSpaceOnUse"><stop class="y35kqz9gt"/><stop offset="1" class="vwk_njbdz"/></linearGradient><linearGradient id="iYle53b" x1="12.057" x2="13.462" y1="26.126" y2="27.034" gradientUnits="userSpaceOnUse"><stop offset=".156" class="h-g_zlb9t"/><stop offset="1" class="fgvaegbje"/></linearGradient><linearGradient id="iGmcC5c" x1="13.143" x2="8.73" y1="22.582" y2="26.843" gradientUnits="userSpaceOnUse"><stop class="y35kqz9gt"/><stop offset="1" class="vwk_njbdz"/></linearGradient><linearGradient id="iMqptOe" x1="13.026" x2="12.105" y1="26.907" y2="25.921" gradientUnits="userSpaceOnUse"><stop class="h-g_zlb9t"/><stop offset="1" class="fgvaegbje"/></linearGradient><filter id="inyK1lm" width="27.663" height="25.676" x="1.962" y="4.418" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.5" dy="-1.5"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.615686 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4022"/></filter><filter id="ibn5exb" width="13.93" height="14.318" x="3.362" y="15.279" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4022" stdDeviation=".375"/></filter><filter id="iOrQl7b" width="6.912" height="6.656" x="12.793" y="23.601" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4022" stdDeviation=".75"/></filter><filter id="iQ1K6Ac" width="7.303" height="5.727" x="9.557" y="7.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4022" stdDeviation=".43"/></filter><filter id="iT5ozqd" width="13.063" height="12.125" x="15.869" y="10.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4022" stdDeviation=".75"/></filter><filter id="iCHdbtc" width="6.912" height="6.656" x="19.901" y="19.313" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4022" stdDeviation=".75"/></filter><filter id="irb3Ltd" width="6.912" height="6.656" x="16.647" y="21.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4022" stdDeviation=".75"/></filter><filter id="izIzpIe" width="19.139" height="13.061" x="10.95" y="5.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.615686 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4022"/></filter><filter id="iCkDrLe" width="10.716" height="7.64" x="11.006" y="5.12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4022" stdDeviation="1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:handshake" /></template>
<style>
.aubc5ccdr {
  stop-color: var(--svg-color--ffcb41, #FFCB41);
  stop-opacity: 0;
}

.bcgy66buw {
  stop-color: var(--svg-color--ffd941, #FFD941);
  stop-opacity: 0;
}

.bep7kfa5k {
  stop-color: var(--svg-color--ffcd43, #FFCD43);
}

.c9cnarajy {
  d: path("M6.814 6.47c.452-.223 1.64-.69 3.579-.512c3.231.468 5.708.842 6.562.98L14.878 8.19a7.6 7.6 0 0 1 1.243 1.64l.385-.442l10.857 9.495a2.229 2.229 0 0 1-1.763 3.886a2.41 2.41 0 0 1-2.997 3.35a2.41 2.41 0 0 1-3.648 1.991a2.452 2.452 0 0 1-4.019 1.381l-8.844-7.71a2.46 2.46 0 0 1-.84-2.006A7.566 7.566 0 0 1 6.813 6.47");
}

.d0le1xg3b {
  fill: var(--svg-color--ffe746, #FFE746);
  d: path("M18.736 9.508c-1.305.32-2.894.806-4.055 1.188a1.276 1.276 0 0 1-1.626-.847c-.174-.603.132-1.242.725-1.45c1.49-.52 3.306-.991 4.606-1.256c.623-.127 1.205.298 1.317.924c.117.655-.321 1.283-.967 1.44");
}

.d7lykbbcp {
  stop-color: var(--svg-color--ffe43e, #FFE43E);
}

.d8d8bfk5a {
  stop-color: var(--svg-color--ee9226, #EE9226);
}

.ddr93pbtf {
  stop-color: var(--svg-color--da725b, #DA725B);
  stop-opacity: 0;
}

.di0rlkb3k {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m18.897 24.132l2.412 2.157");
}

.ex4_2kakc {
  stop-color: var(--svg-color--ffd941, #FFD941);
}

.fgfhc4b1p {
  fill: var(--svg-color--fbb439, #FBB439);
  d: path("m12.128 8.036l.002.006a2.095 2.095 0 0 0 1.71 3.824l.628-.203l.003-.001c.954-.309 2.359-.796 3.125-.948c.238-.048.472.04.655.2l9.093 7.961c1.646-1.446 2.745-3.415 2.745-5.698c0-3.984-3.154-7.213-7.269-7.213c-2.822.14-7.303.729-10.692 2.072");
}

.fgvaegbje {
  stop-color: var(--svg-color--e08407, #E08407);
  stop-opacity: 0;
}

.fiuhwcb4z {
  stop-color: var(--svg-color--f7a91e, #F7A91E);
}

.fj0llis_o {
  stop-color: var(--svg-color--ffea49, #FFEA49);
}

.ft5dv1b6b {
  fill: none;
}

.gdgyw3b4h {
  stop-color: var(--svg-color--ee9226, #EE9226);
  stop-opacity: 0;
}

.ge_39wb5l {
  stop-color: var(--svg-color--ffcd43, #FFCD43);
  stop-opacity: 0;
}

.h-g_zlb9t {
  stop-color: var(--svg-color--e08407, #E08407);
}

.h56ds_bxn {
  stop-color: var(--svg-color--ffdc38, #FFDC38);
  stop-opacity: 0;
}

.hns7l1blj {
  stop-color: var(--svg-color--ffdc38, #FFDC38);
}

.hzvcdyxra {
  stop-color: var(--svg-color--f7a91e, #F7A91E);
  stop-opacity: 0;
}

.j3nb6bcka {
  stop-color: var(--svg-color--ffbe37, #FFBE37);
}

.j5c3bwmeq {
  fill: var(--svg-color--d77a15, #D77A15);
  d: path("M13.208 8.117a20 20 0 0 0-1.754.58l.002.005a1.8 1.8 0 0 0-1.04 1.62c0 .996.827 1.802 1.846 1.802c.248 0 .485-.048.701-.135l.553-.174h.003l.516-.166c3.498-1.126 1.76-1.522-.827-3.532");
}

.l_iu3xbdk {
  stop-color: var(--svg-color--ffe949, #FFE949);
  stop-opacity: 0;
}

.l7_-qjbkm {
  stop-color: var(--svg-color--f48e5a, #F48E5A);
}

.lb5l0hb7w {
  stop-color: var(--svg-color--ffe647, #FFE647);
  stop-opacity: 0;
}

.ltf3mccry {
  d: path("m12.128 8.036l.002.006a2.095 2.095 0 0 0 1.71 3.824l.628-.203l.003-.001c.954-.309 2.359-.796 3.125-.948c.238-.048.472.04.655.2l9.093 7.961c1.646-1.446 2.745-3.415 2.745-5.698c0-3.984-3.154-7.213-7.269-7.213c-2.822.14-7.303.729-10.692 2.072");
}

.m0lqw5bea {
  stop-color: var(--svg-color--ffd741, #FFD741);
}

.maxp1bbvh {
  d: path("M9.024 27.06c-.757-.757-1.07-1.938-.314-2.694l2.557-2.604c.757-.756 1.998-.676 2.806.248c.63.721.756 1.983 0 2.74l-2.31 2.31c-.612.704-1.983.756-2.74 0");
}

.mo5o3wbvd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m18.12 12.42l8.562 7.625");
}

.n212dmbbg {
  stop-color: var(--svg-color--e8766e, #E8766E);
  stop-opacity: 0;
}

.nbwql2bcw {
  stop-color: var(--svg-color--ffcb41, #FFCB41);
}

.ndohv0r2p {
  stop-color: var(--svg-color--f48e5a, #F48E5A);
  stop-opacity: 0;
}

.o8vq4_ixs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m22.15 21.563l2.413 2.156");
}

.qc1f41dre {
  stop-color: var(--svg-color--ffe43e, #FFE43E);
  stop-opacity: 0;
}

.qmsogbc6q {
  d: path("M11.54 29.243c-.653-.785-.716-2.038 0-2.766l1.718-1.53c.82-.833 2.11-.75 2.877.132c.698.8.758 2.232 0 2.976l-1.488 1.54c-.918.765-2.363.542-3.107-.352");
}

.rhhh3kv2j {
  stop-color: var(--svg-color--ffe949, #FFE949);
}

.rp-_jcomq {
  stop-color: var(--svg-color--ffd63f, #FFD63F);
  stop-opacity: 0;
}

.rsj74xbic {
  fill: var(--svg-color--ffb21a, #FFB21A);
  fill-rule: evenodd;
  d: path("M4.682 18.252a1.983 1.983 0 0 0-.112 2.659a2.08 2.08 0 0 0 1.968.728a1.94 1.94 0 0 0 .375 2.22c.552.55 1.377.749 2.076.525c-.12.596.163 1.273.647 1.758c.478.477 1.228.598 1.824.408c-.075.542.087 1.13.446 1.561c.67.806 1.973 1.007 2.8.316l1.343-1.387c.684-.671.63-1.962 0-2.684c-.427-.491-1.034-.708-1.61-.625c.389-.679.235-1.588-.25-2.143c-.49-.56-1.158-.777-1.75-.65a2.04 2.04 0 0 0-.436-2.22c-.627-.615-1.588-.706-2.33-.3a2.002 2.002 0 0 0-3.39-1.793z");
}

.sm1yccbtp {
  d: path("M3.407 21.259a2.2 2.2 0 0 1 .124-2.948l1.775-1.803a2.22 2.22 0 1 1 3.137 3.142l-1.801 1.866c-.918.9-2.413.731-3.235-.257");
}

.t6n1lgw1y {
  stop-color: var(--svg-color--ffea49, #FFEA49);
  stop-opacity: 0;
}

.u-6tkfz7w {
  stop-color: var(--svg-color--da725b, #DA725B);
}

.u9c8p6q2e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.044 25.851l2.411 2.156");
}

.vhsap-b1a {
  stop-color: var(--svg-color--e8766e, #E8766E);
}

.vwk_njbdz {
  stop-color: var(--svg-color--e69429, #E69429);
}

.wyzm6k48s {
  stop-color: var(--svg-color--ffd63f, #FFD63F);
}

.xv8a7ebxl {
  d: path("M6.005 24.53a2.15 2.15 0 0 1-.018-3.027l2.568-2.62c.836-.853 2.241-.891 3.094-.055c.855.84.882 2.279.037 3.13L9.1 24.625c-.838.843-2.254.742-3.096-.097");
}

.y35kqz9gt {
  stop-color: var(--svg-color--ffbc41, #FFBC41);
}

.zaigj4bqx {
  stop-color: var(--svg-color--ffe647, #FFE647);
}

</style>
