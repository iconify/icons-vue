<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#igT68Pd)"><path fill="url(#irYW3Ud)" class="kcyueoyip"/><path fill="url(#iuqfkFb)" class="kcyueoyip"/></g><path fill="url(#iGE8VFK)" class="kcyueoyip"/><path fill="url(#iZYFDad)" class="kcyueoyip"/><path fill="url(#ifTac2b)" class="l07_0dbqf"/><path fill="url(#iXRnC4c)" class="l07_0dbqf"/><path fill="url(#idQywDe)" class="l07_0dbqf"/><path fill="url(#iqxGYJe)" class="l07_0dbqf"/><path fill="url(#iRgjrBc)" class="l07_0dbqf"/><path fill="url(#ibpY2Za)" class="omo55ei7p"/><path fill="url(#iXRISGc)" class="omo55ei7p"/><path fill="url(#iZ0raQd)" class="omo55ei7p"/><path fill="url(#iBaZnkb)" class="omo55ei7p"/><path fill="url(#it68ddd)" class="omo55ei7p"/><path fill="url(#ilo2mCX)" class="di5vknbnb"/><path fill="url(#i4Kd5Oz)" class="di5vknbnb"/><path fill="url(#iNu9WJw)" class="di5vknbnb"/><path fill="url(#iJ8yzpd)" class="di5vknbnb"/><path fill="url(#irdIeEe)" class="di5vknbnb"/><path fill="url(#iVUbrIe)" class="x0r-iunld"/><path fill="url(#iCseWAd)" class="x0r-iunld"/><g filter="url(#idFpH7d)"><path fill="url(#iFbRaRb)" class="dj6v2bcaz"/></g><g filter="url(#i764Nlb)"><path fill="url(#i4Ubu1c)" class="ga9snrw7i"/></g><g filter="url(#if4EJuc)"><path fill="url(#iYFJ3xU)" class="xuqbm07_e"/></g><g filter="url(#iZ2VIub)"><path class="ca8h6_bik"/></g><path fill="url(#ifMMLSb)" class="lbc6c1btw"/><g filter="url(#ixkpsmb)"><path stroke="url(#ikvaPGk)" class="qzkzwyb3r"/></g><g filter="url(#ioaGQod)"><path stroke="url(#iN6t1Hd)" class="a8x78ougi"/></g><g filter="url(#iNAeLQb)"><path stroke="url(#iIUSDee)" class="gged4sbjk"/></g><g filter="url(#iaf2trf)"><path stroke="url(#iFMLsmd)" class="n6n56tbnc"/></g><g filter="url(#i0A5YZd)"><path stroke="url(#ihORmCd)" class="ql2m76c7r"/></g><defs><linearGradient id="iGE8VFK" x1="15.234" x2="15.203" y1="27.866" y2="26.922" gradientUnits="userSpaceOnUse"><stop offset=".291" class="iay0wobaf"/><stop offset=".863" class="ers0gebke"/></linearGradient><linearGradient id="ifTac2b" x1="7.438" x2="7.594" y1="14.641" y2="12.297" gradientUnits="userSpaceOnUse"><stop offset=".308" class="sw2wxmbop"/><stop offset="1" class="j0z4bac7x"/></linearGradient><linearGradient id="iXRnC4c" x1="3.717" x2="5.996" y1="12.174" y2="12.242" gradientUnits="userSpaceOnUse"><stop class="y05mmciwj"/><stop offset="1" class="qhz2ivbif"/></linearGradient><linearGradient id="idQywDe" x1="10.664" x2="10.695" y1="14.821" y2="14.164" gradientUnits="userSpaceOnUse"><stop offset=".07" class="p4bkklbcr"/><stop offset="1" class="wqf0efudb"/></linearGradient><linearGradient id="iRgjrBc" x1="15.836" x2="13.311" y1="14.168" y2="14.042" gradientUnits="userSpaceOnUse"><stop class="tgdzay6_p"/><stop offset="1" class="gqm2cbbrt"/></linearGradient><linearGradient id="ibpY2Za" x1="5.934" x2="6.052" y1="19.326" y2="16.664" gradientUnits="userSpaceOnUse"><stop offset=".018" class="dtzda3szi"/><stop offset="1" class="l9z6pbdcr"/></linearGradient><linearGradient id="iXRISGc" x1="1.571" x2="4.237" y1="16.544" y2="16.637" gradientUnits="userSpaceOnUse"><stop class="zkwth8bgs"/><stop offset="1" class="ylnt-xrmz"/></linearGradient><linearGradient id="iZ0raQd" x1="9.742" x2="9.749" y1="19.589" y2="18.509" gradientUnits="userSpaceOnUse"><stop offset=".07" class="bqjexqfhl"/><stop offset="1" class="szy8jwltp"/></linearGradient><linearGradient id="it68ddd" x1="15.755" x2="12.802" y1="18.54" y2="18.368" gradientUnits="userSpaceOnUse"><stop class="tgdzay6_p"/><stop offset="1" class="gqm2cbbrt"/></linearGradient><linearGradient id="ilo2mCX" x1="7.642" x2="7.649" y1="23.731" y2="21.315" gradientUnits="userSpaceOnUse"><stop offset=".018" class="dtzda3szi"/><stop offset="1" class="l9z6pbdcr"/></linearGradient><linearGradient id="i4Kd5Oz" x1="3.844" x2="6.445" y1="21.203" y2="21.103" gradientUnits="userSpaceOnUse"><stop class="zkwth8bgs"/><stop offset="1" class="ylnt-xrmz"/></linearGradient><linearGradient id="iNu9WJw" x1="10.753" x2="10.682" y1="23.97" y2="22.763" gradientUnits="userSpaceOnUse"><stop offset=".07" class="bqjexqfhl"/><stop offset="1" class="szy8jwltp"/></linearGradient><linearGradient id="irdIeEe" x1="15.837" x2="13.339" y1="23.017" y2="22.882" gradientUnits="userSpaceOnUse"><stop class="tgdzay6_p"/><stop offset="1" class="gqm2cbbrt"/></linearGradient><linearGradient id="iVUbrIe" x1="10.394" x2="10.573" y1="23.007" y2="24.785" gradientUnits="userSpaceOnUse"><stop offset=".169" class="t2dpz7bxy"/><stop offset=".828" class="ehf63q_2n"/></linearGradient><linearGradient id="iCseWAd" x1="7.108" x2="8.784" y1="26.169" y2="26.116" gradientUnits="userSpaceOnUse"><stop class="vd-rl245x"/><stop offset="1" class="ot9y23lae"/></linearGradient><linearGradient id="ikvaPGk" x1="14.619" x2="13.939" y1="5.43" y2="10.666" gradientUnits="userSpaceOnUse"><stop class="hzfw6tb8l"/><stop offset="1" class="grl1s9biz"/></linearGradient><linearGradient id="iN6t1Hd" x1="5.777" x2="5.773" y1="11.799" y2="12.235" gradientUnits="userSpaceOnUse"><stop class="vbdndjbfe"/><stop offset="1" class="p_1nh2bjk"/></linearGradient><linearGradient id="iIUSDee" x1="3.513" x2="3.51" y1="16.014" y2="16.429" gradientUnits="userSpaceOnUse"><stop class="vbdndjbfe"/><stop offset="1" class="p_1nh2bjk"/></linearGradient><linearGradient id="iFMLsmd" x1="6.148" x2="6.126" y1="20.495" y2="21.437" gradientUnits="userSpaceOnUse"><stop class="vbdndjbfe"/><stop offset="1" class="p_1nh2bjk"/></linearGradient><linearGradient id="ihORmCd" x1="8.84" x2="8.838" y1="25.033" y2="25.286" gradientUnits="userSpaceOnUse"><stop class="vbdndjbfe"/><stop offset="1" class="p_1nh2bjk"/></linearGradient><radialGradient id="irYW3Ud" cx="0" cy="0" r="1" gradientTransform="rotate(170.048 14.091 8.795)scale(27.1022 28.0881)" gradientUnits="userSpaceOnUse"><stop class="ndzgtxbgp"/><stop offset=".467" class="tgdzay6_p"/></radialGradient><radialGradient id="iuqfkFb" cx="0" cy="0" r="1" gradientTransform="rotate(-14.736 90.3 -22.036)scale(23.1871 22.2856)" gradientUnits="userSpaceOnUse"><stop offset=".776" class="lwp_jvbfd"/><stop offset=".943" class="gklbce_xe"/></radialGradient><radialGradient id="iZYFDad" cx="0" cy="0" r="1" gradientTransform="rotate(67.003 -1.356 19.57)scale(15.0532 25.7656)" gradientUnits="userSpaceOnUse"><stop offset=".963" class="wxk57r3yi"/><stop offset="1" class="bseoa6bkw"/></radialGradient><radialGradient id="iqxGYJe" cx="0" cy="0" r="1" gradientTransform="matrix(-8.46752 .41117 -.28996 -5.97146 12.173 12.538)" gradientUnits="userSpaceOnUse"><stop offset=".912" class="u2bjpobvi"/><stop offset="1" class="tcqyb4wer"/></radialGradient><radialGradient id="iBaZnkb" cx="0" cy="0" r="1" gradientTransform="rotate(177.62 5.558 8.573)scale(9.9186 5.9904)" gradientUnits="userSpaceOnUse"><stop offset=".912" class="u2bjpobvi"/><stop offset="1" class="tcqyb4wer"/></radialGradient><radialGradient id="iJ8yzpd" cx="0" cy="0" r="1" gradientTransform="rotate(173.151 5.33 10.825)scale(8.13765 5.28006)" gradientUnits="userSpaceOnUse"><stop offset=".92" class="u2bjpobvi"/><stop offset="1" class="tcqyb4wer"/></radialGradient><radialGradient id="iFbRaRb" cx="0" cy="0" r="1" gradientTransform="matrix(2.5625 -.0872 .07968 2.34138 14.948 14.812)" gradientUnits="userSpaceOnUse"><stop class="hvc5ocbnd"/><stop offset="1" class="q8ipsybsi"/></radialGradient><radialGradient id="i4Ubu1c" cx="0" cy="0" r="1" gradientTransform="matrix(3.03125 -.09153 .07422 2.45803 14.43 18.956)" gradientUnits="userSpaceOnUse"><stop class="hvc5ocbnd"/><stop offset="1" class="q8ipsybsi"/></radialGradient><radialGradient id="iYFJ3xU" cx="0" cy="0" r="1" gradientTransform="matrix(2.75258 -.09773 .09316 2.62374 15.136 23.411)" gradientUnits="userSpaceOnUse"><stop class="hvc5ocbnd"/><stop offset="1" class="q8ipsybsi"/></radialGradient><radialGradient id="ifMMLSb" cx="0" cy="0" r="1" gradientTransform="rotate(-139.172 9.594 2.931)scale(4.70811 1.85451)" gradientUnits="userSpaceOnUse"><stop class="c9nxn5gus"/><stop offset=".251" class="r_4gaccat"/><stop offset="1" class="fqxvz87tf"/></radialGradient><filter id="igT68Pd" width="28.465" height="24.039" x="1.817" y="3.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.258824 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6918"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.403922 0 0 0 0 0.25098 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_6918" result="effect2_innerShadow_20020_6918"/></filter><filter id="idFpH7d" width="3.163" height="3.347" x="14.648" y="13.138" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6918" stdDeviation=".15"/></filter><filter id="i764Nlb" width="3.631" height="3.483" x="14.129" y="17.214" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6918" stdDeviation=".15"/></filter><filter id="if4EJuc" width="3.353" height="3.679" x="14.836" y="21.572" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6918" stdDeviation=".15"/></filter><filter id="iZ2VIub" width="6.246" height="16.916" x="13.694" y="10.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6918" stdDeviation=".75"/></filter><filter id="ixkpsmb" width="12.792" height="9.153" x="13.198" y="4.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6918" stdDeviation=".625"/></filter><filter id="ioaGQod" width="14.446" height="4.713" x="4.013" y="9.741" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6918" stdDeviation=".75"/></filter><filter id="iNAeLQb" width="16.246" height="4.69" x="1.813" y="13.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6918" stdDeviation=".75"/></filter><filter id="iaf2trf" width="13.313" height="4.25" x="4.344" y="18.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6918" stdDeviation=".75"/></filter><filter id="i0A5YZd" width="10.701" height="4.519" x="6.944" y="22.947" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6918" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:leftwards-hand-medium-dark" /></template>
<style>
.a8x78ougi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m6.138 11.866l10.196.463");
}

.bqjexqfhl {
  stop-color: var(--svg-color--4e2723, #4E2723);
}

.bseoa6bkw {
  stop-color: var(--svg-color--825074, #825074);
}

.c9nxn5gus {
  stop-color: var(--svg-color--3b2018, #3B2018);
}

.ca8h6_bik {
  stroke: var(--svg-color--7e544f, #7E544F);
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.343 12.153c-1.146 2-2.663 7.437.437 13.187");
}

.di5vknbnb {
  d: path("M5.1 19.337a2.406 2.406 0 0 0 1.4 4.393l9.813-.214v-4.179z");
}

.dj6v2bcaz {
  d: path("M17.51 16.186c-.835-.896-2.062-1.227-2.562-1.216c1.3-.15 2.25-1.084 2.563-1.532z");
}

.dtzda3szi {
  stop-color: var(--svg-color--744356, #744356);
}

.ehf63q_2n {
  stop-color: var(--svg-color--613a33, #613A33);
  stop-opacity: 0;
}

.ers0gebke {
  stop-color: var(--svg-color--7b4360, #7B4360);
  stop-opacity: 0;
}

.fqxvz87tf {
  stop-color: var(--svg-color--57322b, #57322B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ga9snrw7i {
  d: path("M17.46 20.398c-1.005-.887-2.44-1.085-3.03-1.072c1.537-.178 2.66-1.282 3.03-1.812z");
}

.gged4sbjk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m3.938 16.078l11.996.44");
}

.gklbce_xe {
  stop-color: var(--svg-color--a57e72, #A57E72);
}

.gqm2cbbrt {
  stop-color: var(--svg-color--825656, #825656);
  stop-opacity: 0;
}

.grl1s9biz {
  stop-color: var(--svg-color--95705e, #95705E);
  stop-opacity: 0;
}

.hvc5ocbnd {
  stop-color: var(--svg-color--6d453e, #6D453E);
}

.hzfw6tb8l {
  stop-color: var(--svg-color--95705e, #95705E);
}

.iay0wobaf {
  stop-color: var(--svg-color--7d4470, #7D4470);
}

.j0z4bac7x {
  stop-color: var(--svg-color--77494c, #77494C);
  stop-opacity: 0;
}

.kcyueoyip {
  d: path("M4.29 14.502a2.406 2.406 0 0 0-.135 4.809l.945.027a2.406 2.406 0 0 0 1.4 4.393l1.37-.026a2.406 2.406 0 0 0 1.736 4.16l8.822-.336c1.33-.005 3.695-.149 5.76-1.003c3.267-1.208 5.595-4.341 5.595-8.016c0-3.716-2.38-6.877-5.702-8.055c-2.108-.888-4.283-2.361-5.205-2.986l-.06-.042l-2.82-2.098a2.536 2.536 0 0 0-3.054 4.05l1.424 1.088l-7.953-.343a2.385 2.385 0 0 0-1.378 4.399z");
}

.l07_0dbqf {
  d: path("m6.181 10.125l10.136.423v4.404l-11.288-.433a2.384 2.384 0 0 1 1.152-4.394");
}

.l9z6pbdcr {
  stop-color: var(--svg-color--744356, #744356);
  stop-opacity: 0;
}

.lbc6c1btw {
  d: path("M17.684 10.593L12.69 5.568q-.13.13-.243.281a2.536 2.536 0 0 0 .495 3.53l1.424 1.088z");
}

.lwp_jvbfd {
  stop-color: var(--svg-color--956c66, #956C66);
  stop-opacity: 0;
}

.n6n56tbnc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M6.469 20.64h9.062");
}

.ndzgtxbgp {
  stop-color: var(--svg-color--a0796f, #A0796F);
}

.omo55ei7p {
  d: path("M1.815 16.829a2.406 2.406 0 0 1 2.472-2.337c4.003.112 8.021.29 12.03.436v4.398H5.093l-.941-.025a2.406 2.406 0 0 1-2.337-2.472");
}

.ot9y23lae {
  stop-color: var(--svg-color--623d38, #623D38);
  stop-opacity: 0;
}

.p_1nh2bjk {
  stop-color: var(--svg-color--876153, #876153);
  stop-opacity: 0;
}

.p4bkklbcr {
  stop-color: var(--svg-color--553026, #553026);
}

.q8ipsybsi {
  stop-color: var(--svg-color--6d453e, #6D453E);
  stop-opacity: 0;
}

.qhz2ivbif {
  stop-color: var(--svg-color--755448, #755448);
  stop-opacity: 0;
}

.ql2m76c7r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m9.069 25.34l6.45-.268");
}

.qzkzwyb3r {
  stroke-linecap: round;
  d: path("M14.948 6.252c1.48 1.398 5.871 4.074 9.292 5.653");
}

.r_4gaccat {
  stop-color: var(--svg-color--57322b, #57322B);
}

.sw2wxmbop {
  stop-color: var(--svg-color--77494c, #77494C);
}

.szy8jwltp {
  stop-color: var(--svg-color--75444d, #75444D);
  stop-opacity: 0;
}

.t2dpz7bxy {
  stop-color: var(--svg-color--4c2623, #4C2623);
}

.tcqyb4wer {
  stop-color: var(--svg-color--805d54, #805D54);
}

.tgdzay6_p {
  stop-color: var(--svg-color--825656, #825656);
}

.u2bjpobvi {
  stop-color: var(--svg-color--805d54, #805D54);
  stop-opacity: 0;
}

.vbdndjbfe {
  stop-color: var(--svg-color--876153, #876153);
}

.vd-rl245x {
  stop-color: var(--svg-color--623d38, #623D38);
}

.wqf0efudb {
  stop-color: var(--svg-color--6b403b, #6B403B);
  stop-opacity: 0;
}

.wxk57r3yi {
  stop-color: var(--svg-color--7f4a62, #7F4A62);
  stop-opacity: 0;
}

.x0r-iunld {
  d: path("M7.87 23.705a2.406 2.406 0 0 0 1.736 4.16l6.91-.271c0-1.342-.852-3.157-.852-4.078z");
}

.xuqbm07_e {
  d: path("M17.888 24.95c-1.038-1.051-2.16-1.434-2.752-1.421c1.538-.178 2.383-1.127 2.752-1.657z");
}

.y05mmciwj {
  stop-color: var(--svg-color--755448, #755448);
}

.ylnt-xrmz {
  stop-color: var(--svg-color--76574c, #76574C);
  stop-opacity: 0;
}

.zkwth8bgs {
  stop-color: var(--svg-color--76574c, #76574C);
}

</style>
