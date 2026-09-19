<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><g filter="url(#is24Fdb)"><path fill="url(#iA1L6mV)" class="esghq7bfr"/></g><g filter="url(#iVqtUFb)"><path class="pfi3mg4zt"/></g><g filter="url(#imvsXYb)"><path class="srh1mgb2t"/></g><g filter="url(#iNPWdzd)"><circle class="ji0-fe8jy"/></g><g filter="url(#icl6CFc)"><circle class="uoa87yvct"/></g><g filter="url(#inCevZb)"><path clip-rule="evenodd" class="zzlchdcqw"/></g><circle class="ky6rh0p0r"/><circle class="yav14pbwj"/><path clip-rule="evenodd" class="k_d_gtb5r"/><path stroke="url(#iLSyOfv)" class="m-m-3bc2z"/><path stroke="url(#iHrIX0i)" class="bmogitbqp"/><path stroke="url(#i2200Hb)" class="jot2jxbzq"/><path fill="url(#iUrQ7ML)" clip-rule="evenodd" class="e77kjxqlr"/><path fill="url(#ielCfnc)" clip-rule="evenodd" class="e77kjxqlr"/><path fill="url(#iQkn3ed)" clip-rule="evenodd" class="e77kjxqlr"/><path fill="url(#ixFC0Fc)" clip-rule="evenodd" class="vjtwsbbib"/><path fill="url(#iGhosyb)" clip-rule="evenodd" class="vjtwsbbib"/><path fill="url(#iuppYkd)" clip-rule="evenodd" class="vjtwsbbib"/><path fill="url(#icysrCc)" clip-rule="evenodd" class="vjtwsbbib"/><g filter="url(#i9824td)"><circle stroke="url(#iJomr4d)" class="h9ttddbsv"/></g><g filter="url(#ideMvld)"><ellipse fill="url(#i4Pkeud)" transform="rotate(44.538 27.114 11.571)" class="mve88cc6g"/></g><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iLSyOfv" cx="0" cy="0" r="1" gradientTransform="matrix(1.00489 -7.69537 15.46203 2.01909 11.307 8.068)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="m8pwa1xcy"/><stop offset=".297" class="lwri579ja"/><stop offset=".438" class="gw349qs5e"/></radialGradient><radialGradient id="iHrIX0i" cx="0" cy="0" r="1" gradientTransform="matrix(-.10646 -6.55826 12.1842 -.19779 21.17 5.37)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="m8pwa1xcy"/><stop offset=".297" class="lwri579ja"/><stop offset=".438" class="gw349qs5e"/></radialGradient><radialGradient id="i2200Hb" cx="0" cy="0" r="1" gradientTransform="matrix(2.81237 -14.74998 16.00664 3.05198 15.512 22.129)" gradientUnits="userSpaceOnUse"><stop offset=".07" class="m8pwa1xcy"/><stop offset=".297" class="lwri579ja"/><stop offset=".438" class="gw349qs5e"/></radialGradient><radialGradient id="ixFC0Fc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.43751 7.0125 -7.53775 -3.69499 24.689 10.564)" gradientUnits="userSpaceOnUse"><stop class="m-zvk4b9x"/><stop offset="1" class="cuggwh83m"/></radialGradient><radialGradient id="iuppYkd" cx="0" cy="0" r="1" gradientTransform="rotate(106.682 8.347 12.307)scale(9.68901 9.47937)" gradientUnits="userSpaceOnUse"><stop offset=".679" class="xkre6ac1u"/><stop offset="1" class="ben3h2bxq"/></radialGradient><radialGradient id="icysrCc" cx="0" cy="0" r="1" gradientTransform="matrix(2.9688 -5.68747 10.31888 5.38633 21.189 15.752)" gradientUnits="userSpaceOnUse"><stop class="ix0rqtbbf"/><stop offset=".208" class="fl01f9bqq"/></radialGradient><filter id="is24Fdb" width="5.218" height="4.993" x="22.297" y="21.028" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6815_5229" stdDeviation=".25"/></filter><filter id="iVqtUFb" width="10.483" height="6.212" x="15.141" y="2.357" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6815_5229" stdDeviation="1"/></filter><filter id="imvsXYb" width="10.483" height="6.212" x="4.351" y="4.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6815_5229" stdDeviation="1"/></filter><filter id="iNPWdzd" width="12.526" height="12.526" x="14.12" y="6.751" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6815_5229" stdDeviation=".5"/></filter><filter id="icl6CFc" width="10.21" height="10.21" x="4.648" y="7.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6815_5229" stdDeviation=".5"/></filter><filter id="inCevZb" width="4.571" height="18.637" x="23.069" y="9.376" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6815_5229" stdDeviation="1"/></filter><filter id="i9824td" width="11.187" height="11.188" x="15.861" y="6.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6815_5229" stdDeviation=".15"/></filter><filter id="ideMvld" width="1.614" height="1.613" x="26.306" y="10.765" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6815_5229" stdDeviation=".125"/></filter><linearGradient id="iA1L6mV" x1="26.486" x2="24.846" y1="26.5" y2="24.992" gradientUnits="userSpaceOnUse"><stop class="mf80-5e1u"/><stop offset="1" class="r4k60ccjj"/></linearGradient><linearGradient id="iUrQ7ML" x1="27.292" x2="23.68" y1="12.376" y2="13.077" gradientUnits="userSpaceOnUse"><stop class="c-95v5b2p"/><stop offset="1" class="hokpuib7w"/></linearGradient><linearGradient id="ielCfnc" x1="27.954" x2="26.126" y1="19.47" y2="19.47" gradientUnits="userSpaceOnUse"><stop class="b01j4q4ln"/><stop offset="1" class="tboaebtrz"/></linearGradient><linearGradient id="iQkn3ed" x1="28.439" x2="24.308" y1="8.189" y2="9.039" gradientUnits="userSpaceOnUse"><stop offset=".679" class="g0qz5txzg"/><stop offset="1" class="g9sedwv1j"/></linearGradient><linearGradient id="iGhosyb" x1="22.814" x2="27.954" y1="13.095" y2="19.001" gradientUnits="userSpaceOnUse"><stop class="b01j4q4ln"/><stop offset="1" class="tboaebtrz"/></linearGradient><linearGradient id="iJomr4d" x1="24.636" x2="21.701" y1="6.434" y2="14.313" gradientUnits="userSpaceOnUse"><stop class="tbd-1abnn"/><stop offset="1" class="l3gl6kbcb"/></linearGradient><linearGradient id="i4Pkeud" x1="26.923" x2="27.02" y1="10.981" y2="12.183" gradientUnits="userSpaceOnUse"><stop class="tbd-1abnn"/><stop offset="1" class="l3gl6kbcb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:face-with-monocle" /></template>
<style>
.b01j4q4ln {
  stop-color: var(--svg-color--8c8693, #8C8693);
  stop-opacity: 0;
}

.ben3h2bxq {
  stop-color: var(--svg-color--987ab5, #987AB5);
}

.bmogitbqp {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M18.91 4.369s.978-.78 2.472-.78s2.71.912 2.71.912");
}

.c-95v5b2p {
  stop-color: var(--svg-color--cac6d5, #CAC6D5);
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.cuggwh83m {
  stop-color: var(--svg-color--938d9a, #938D9A);
}

.e77kjxqlr {
  fill-rule: evenodd;
  d: path("M27.354 11.376a.6.6 0 0 1 .6.6v13.438a.6.6 0 0 1-1.2 0V11.976a.6.6 0 0 1 .6-.6");
}

.esghq7bfr {
  d: path("m26.684 25.521l.33-.324l-2.815-3.669l-1.402 2.34z");
}

.fl01f9bqq {
  stop-color: var(--svg-color--837890, #837890);
  stop-opacity: 0;
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft5dv1b6b {
  fill: none;
}

.g0qz5txzg {
  stop-color: var(--svg-color--b08cd2, #B08CD2);
  stop-opacity: 0;
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.g9sedwv1j {
  stop-color: var(--svg-color--bb96de, #BB96DE);
}

.gw349qs5e {
  stop-color: var(--svg-color--4b2744, #4B2744);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.h9ttddbsv {
  cx: 21.454px;
  cy: 11.923px;
  r: 5.194px;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.hokpuib7w {
  stop-color: var(--svg-color--b9b2c1, #B9B2C1);
}

.ix0rqtbbf {
  stop-color: var(--svg-color--837890, #837890);
}

.ji0-fe8jy {
  cx: 20.383px;
  cy: 13.014px;
  r: 5.263px;
  fill: var(--svg-color--cd6330, #CD6330);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
}

.jot2jxbzq {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-8px, 1.8px);
  d: path("M13.098 18.62s1.35-1.062 3.358-.556c1.673.421 2.446 1.944 2.446 1.944");
}

.k_d_gtb5r {
  fill: var(--svg-color--402a32, #402A32);
  fill-rule: evenodd;
  d: path("M21.001 8.251A3 3 0 1 0 21 14.25a3 3 0 0 0 .001-5.999m-11 .25a3 3 0 1 0 0 6a3 3 0 0 0 0-6");
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.ky6rh0p0r {
  cx: 21.454px;
  cy: 11.923px;
  r: 4.453px;
  fill: var(--svg-color--fff, #fff);
}

.l3gl6kbcb {
  stop-color: var(--svg-color--b5aebe, #B5AEBE);
  stop-opacity: 0;
}

.lwri579ja {
  stop-color: var(--svg-color--5f4357, #5F4357);
}

.m-m-3bc2z {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M7.962 6.613s.873-.756 2.434-.756c1.665 0 2.644.888 2.644.888");
}

.m-zvk4b9x {
  stop-color: var(--svg-color--a09da8, #A09DA8);
}

.m8pwa1xcy {
  stop-color: var(--svg-color--2e1529, #2E1529);
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mf80-5e1u {
  stop-color: var(--svg-color--b95a2d, #B95A2D);
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.mve88cc6g {
  cx: 27.114px;
  cy: 11.571px;
  rx: 0.581px;
  ry: 0.531px;
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.pfi3mg4zt {
  stroke: var(--svg-color--d46a37, #D46A37);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-opacity: 0.6;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M17.791 5.787s.979-.78 2.473-.78s2.71.912 2.71.912");
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.r4k60ccjj {
  stop-color: var(--svg-color--d46a37, #D46A37);
  stop-opacity: 0;
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.srh1mgb2t {
  stroke: var(--svg-color--ac552b, #AC552B);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-opacity: 0.6;
  stroke-width: var(--svg-stroke-width--1-3px, 1.3px);
  d: path("M7.001 7.822s.979-.78 2.473-.78s2.71.913 2.71.913");
}

.tbd-1abnn {
  stop-color: var(--svg-color--b5aebe, #B5AEBE);
}

.tboaebtrz {
  stop-color: var(--svg-color--8c8693, #8C8693);
}

.uoa87yvct {
  cx: 9.753px;
  cy: 12.358px;
  r: 4.105px;
  fill: var(--svg-color--d56a37, #D56A37);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
}

.vjtwsbbib {
  fill-rule: evenodd;
  d: path("M27.357 12.958c-.209.121-.401.294-.468.526a5.653 5.653 0 1 1 0-3.122c.067.232.26.405.468.526a1.195 1.195 0 0 1 0 2.07m-1.45-1.035a4.453 4.453 0 1 1-8.906 0a4.453 4.453 0 0 1 8.906 0");
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.xkre6ac1u {
  stop-color: var(--svg-color--987ab5, #987AB5);
  stop-opacity: 0;
}

.yav14pbwj {
  cx: 10.22px;
  cy: 11.97px;
  r: 4.219px;
  fill: var(--svg-color--fff, #fff);
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

.zzlchdcqw {
  fill: var(--svg-color--df7644, #DF7644);
  fill-rule: evenodd;
  d: path("M25.354 11.376c.158 0 .286.269.286.6v13.438c0 .331-.128.6-.286.6s-.285-.269-.285-.6V11.976c0-.331.128-.6.285-.6");
}

</style>
