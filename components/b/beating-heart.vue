<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iiIt3ue)" class="rjm24xbrc"/><path fill="url(#iZSRNEc)" class="rjm24xbrc"/><path fill="url(#iNhCr7b)" class="rjm24xbrc"/><path fill="url(#iRFEEod)" class="rjm24xbrc"/><path fill="url(#iZ0cnBd)" class="rjm24xbrc"/><path fill="url(#iyDtrUp)" class="rjm24xbrc"/><path fill="url(#iueglUc)" class="i-1cflbel"/><g filter="url(#issf8zI)"><path class="z55bs73lq"/></g><g filter="url(#i0xLPLb)"><ellipse fill="url(#iiD7WFX)" transform="rotate(-44.19 24.063 13.094)" class="zvgzaacyw"/></g><g filter="url(#i6ajwgc)"><ellipse fill="url(#ikalzLQ)" transform="rotate(-128.955 13.718 13.54)" class="aokayl72w"/></g><path fill="url(#iTo6ZDb)" clip-rule="evenodd" class="rm9i_1rpx"/><path fill="url(#idnKXVc)" clip-rule="evenodd" class="rm9i_1rpx"/><g filter="url(#iG0YZDb)"><path stroke="url(#il3QM8c)" class="xytj_udyc"/></g><path fill="url(#iEBGQ7b)" clip-rule="evenodd" class="ppiw1b__t"/><path fill="url(#iCC5hhc)" clip-rule="evenodd" class="ppiw1b__t"/><g filter="url(#iJcv9eb)"><path stroke="url(#i1WkIrd)" class="rumepbbob"/></g><path fill="url(#iFzGVEd)" clip-rule="evenodd" class="t5fy_6xue"/><path fill="url(#iWmgWvc)" clip-rule="evenodd" class="t5fy_6xue"/><path fill="url(#iAuSrPb)" clip-rule="evenodd" class="wj1z9qbob"/><path fill="url(#it9OV6d)" clip-rule="evenodd" class="wj1z9qbob"/><g filter="url(#iYvy0cd)"><path stroke="url(#isqw9XP)" class="qakbc_bst"/></g><g filter="url(#iXXLEKd)"><path stroke="url(#ieCPNId)" class="domb0z73a"/></g><g filter="url(#imgf4bD)"><circle class="obzwswbgb"/></g><g filter="url(#irc7O9b)"><circle class="ib6wj4bjs"/></g><defs><linearGradient id="iZ0cnBd" x1="17.891" x2="24.851" y1="17.37" y2="25.654" gradientUnits="userSpaceOnUse"><stop offset=".694" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></linearGradient><linearGradient id="iyDtrUp" x1="17.028" x2="8.859" y1="17.716" y2="26.919" gradientUnits="userSpaceOnUse"><stop offset=".694" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></linearGradient><linearGradient id="iueglUc" x1="19.698" x2="17.257" y1="11.474" y2="8.793" gradientUnits="userSpaceOnUse"><stop offset=".41" class="k0jhnr2iw"/><stop offset=".834" class="yxx9jebfv"/></linearGradient><linearGradient id="idnKXVc" x1="12.095" x2="8.095" y1="6.452" y2="7.002" gradientUnits="userSpaceOnUse"><stop class="vgsv-4bxn"/><stop offset="1" class="l6w9fiiic"/></linearGradient><linearGradient id="il3QM8c" x1="9.666" x2="6.509" y1="5.541" y2="7.205" gradientUnits="userSpaceOnUse"><stop class="dhj3xbbcu"/><stop offset="1" class="pl211ybaw"/></linearGradient><linearGradient id="iEBGQ7b" x1="3.752" x2="8.964" y1="7.052" y2="4.059" gradientUnits="userSpaceOnUse"><stop offset=".047" class="pgcy-ekrs"/><stop offset="1" class="p3pp_8bno"/></linearGradient><linearGradient id="iCC5hhc" x1="14.005" x2="7.641" y1="4.849" y2="5.817" gradientUnits="userSpaceOnUse"><stop class="vgsv-4bxn"/><stop offset=".578" class="l6w9fiiic"/></linearGradient><linearGradient id="i1WkIrd" x1="9.017" x2="4.043" y1="3.518" y2="6.08" gradientUnits="userSpaceOnUse"><stop class="dhj3xbbcu"/><stop offset="1" class="pl211ybaw"/></linearGradient><linearGradient id="iFzGVEd" x1="26.322" x2="22.905" y1="7.977" y2="6.203" gradientUnits="userSpaceOnUse"><stop offset=".047" class="pgcy-ekrs"/><stop offset="1" class="p3pp_8bno"/></linearGradient><linearGradient id="iWmgWvc" x1="27.095" x2="25.196" y1="9.158" y2="6.993" gradientUnits="userSpaceOnUse"><stop offset=".108" class="um5epfuly"/><stop offset="1" class="l6w9fiiic"/></linearGradient><linearGradient id="iAuSrPb" x1="28.248" x2="23.036" y1="7.052" y2="4.059" gradientUnits="userSpaceOnUse"><stop offset=".047" class="pgcy-ekrs"/><stop offset="1" class="p3pp_8bno"/></linearGradient><linearGradient id="it9OV6d" x1="29.283" x2="26.783" y1="8.815" y2="5.372" gradientUnits="userSpaceOnUse"><stop offset=".108" class="um5epfuly"/><stop offset="1" class="l6w9fiiic"/></linearGradient><linearGradient id="isqw9XP" x1="27.949" x2="22.988" y1="3.426" y2="6.431" gradientUnits="userSpaceOnUse"><stop class="dhj3xbbcu"/><stop offset="1" class="ct6s0gfeg"/></linearGradient><linearGradient id="ieCPNId" x1="29.146" x2="24.185" y1="5.676" y2="8.68" gradientUnits="userSpaceOnUse"><stop class="dhj3xbbcu"/><stop offset="1" class="ct6s0gfeg"/></linearGradient><filter id="issf8zI" width="7.925" height="12.536" x="14.983" y="9.963" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_4954" stdDeviation="1"/></filter><filter id="i0xLPLb" width="9.239" height="9.176" x="19.444" y="8.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_4954" stdDeviation=".75"/></filter><filter id="i6ajwgc" width="9.972" height="10.827" x="8.732" y="8.127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_4954" stdDeviation=".75"/></filter><filter id="iG0YZDb" width="5.894" height="2.636" x="4.742" y="4.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_4954" stdDeviation=".125"/></filter><filter id="iJcv9eb" width="8.738" height="4.099" x="2.164" y="2.678" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_4954" stdDeviation=".125"/></filter><filter id="iYvy0cd" width="9.425" height="3.557" x="20.07" y="2.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_4954" stdDeviation=".125"/></filter><filter id="iXXLEKd" width="6.04" height="2.639" x="21.267" y="5.013" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_4954" stdDeviation=".125"/></filter><filter id="imgf4bD" width="1.324" height="1.324" x="19.699" y="2.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_4954" stdDeviation=".25"/></filter><filter id="irc7O9b" width="1.324" height="1.324" x="21.006" y="4.87" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_4954" stdDeviation=".25"/></filter><radialGradient id="iiIt3ue" cx="0" cy="0" r="1" gradientTransform="matrix(0 -28.302 48.1134 0 18.909 28.5)" gradientUnits="userSpaceOnUse"><stop class="ejc52zb_a"/><stop offset=".596" class="xg2pw8btp"/><stop offset="1" class="r-3kexbeb"/></radialGradient><radialGradient id="iZSRNEc" cx="0" cy="0" r="1" gradientTransform="rotate(142.986 9.025 10.375)scale(22.7831 42.6749)" gradientUnits="userSpaceOnUse"><stop offset=".483" class="fdfp5-b0w"/><stop offset=".834" class="lj35z3s3o"/></radialGradient><radialGradient id="iNhCr7b" cx="0" cy="0" r="1" gradientTransform="rotate(-158.663 11.695 7.535)scale(19.7624 27.9369)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="fdfp5-b0w"/><stop offset=".834" class="lj35z3s3o"/></radialGradient><radialGradient id="iRFEEod" cx="0" cy="0" r="1" gradientTransform="rotate(90 .318 15.675)scale(17.1998)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></radialGradient><radialGradient id="iiD7WFX" cx="0" cy="0" r="1" gradientTransform="rotate(-176.775 14.046 6.54)scale(5.34737 3.61079)" gradientUnits="userSpaceOnUse"><stop class="pl211ybaw"/><stop offset="1" class="qnbh2pn9v"/></radialGradient><radialGradient id="ikalzLQ" cx="0" cy="0" r="1" gradientTransform="rotate(-178.667 8.303 7.01)scale(9.81495 5.19821)" gradientUnits="userSpaceOnUse"><stop class="pl211ybaw"/><stop offset="1" class="qnbh2pn9v"/></radialGradient><radialGradient id="iTo6ZDb" cx="0" cy="0" r="1" gradientTransform="rotate(-112.35 6.691 .793)scale(2.54758 9.11482)" gradientUnits="userSpaceOnUse"><stop class="ejc52zb_a"/><stop offset="1" class="xg2pw8btp"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:beating-heart" /></template>
<style>
.aokayl72w {
  cx: 13.718px;
  cy: 13.54px;
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 4.612px;
  ry: 2.488px;
}

.ct6s0gfeg {
  stop-color: var(--svg-color--ff93ba, #FF93BA);
  stop-opacity: 0.6;
}

.dhj3xbbcu {
  stop-color: var(--svg-color--ff93ba, #FF93BA);
  stop-opacity: 0;
}

.domb0z73a {
  stroke-linecap: round;
  stroke-opacity: 0.75;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M21.668 5.533c1.718-.281 3.38-.203 5.24 1.72");
}

.ejc52zb_a {
  stop-color: var(--svg-color--f12e52, #F12E52);
}

.fdfp5-b0w {
  stop-color: var(--svg-color--b91d43, #B91D43);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.i-1cflbel {
  d: path("M16.284 10.558c.88.82 2.256.574 3.032-.346c.982-1.164 2.333-2.295 4.087-2.407c-1.587-.305-3.316.03-4.84 1.228c-.13.103-.27.21-.412.319c-.422.322-.87.665-1.211.996c-.22.214-.607.236-.835.03L16 10.284c.08.08.176.174.284.274");
}

.ib6wj4bjs {
  cx: 21.668px;
  cy: 5.532px;
  r: 0.162px;
  fill: var(--svg-color--ff93ba, #FF93BA);
}

.k0jhnr2iw {
  stop-color: var(--svg-color--c12372, #C12372);
  stop-opacity: 0;
}

.l6w9fiiic {
  stop-color: var(--svg-color--ce2654, #CE2654);
  stop-opacity: 0;
}

.lj35z3s3o {
  stop-color: var(--svg-color--b91d43, #B91D43);
}

.obzwswbgb {
  cx: 20.361px;
  cy: 3.33px;
  r: 0.162px;
  fill: var(--svg-color--ff93ba, #FF93BA);
}

.p3pp_8bno {
  stop-color: var(--svg-color--ff4781, #FF4781);
}

.pgcy-ekrs {
  stop-color: var(--svg-color--ff1a44, #FF1A44);
}

.pl211ybaw {
  stop-color: var(--svg-color--ff93ba, #FF93BA);
}

.ppiw1b__t {
  fill-rule: evenodd;
  d: path("M11.452 4.03C6.244 3.09 3.73 6.05 3.094 6.831a.6.6 0 1 1-.93-.758c.738-.906 3.647-4.282 9.501-3.224a.6.6 0 1 1-.213 1.181");
}

.qakbc_bst {
  stroke-linecap: round;
  stroke-opacity: 0.75;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M20.47 3.284c1.72-.282 5.907-.579 8.625 2.593");
}

.qnbh2pn9v {
  stop-color: var(--svg-color--ff73a6, #FF73A6);
  stop-opacity: 0;
}

.qudiit10p {
  stop-color: var(--svg-color--ff7af2, #FF7AF2);
  stop-opacity: 0;
}

.r-3kexbeb {
  stop-color: var(--svg-color--ff4ec6, #FF4EC6);
}

.rjm24xbrc {
  d: path("M15.584 28.66a1.71 1.71 0 0 0 1.708-.02c3.129-1.812 8.435-5.873 10.534-11.13c3.118-6.925-4.203-12.453-9.262-8.477c-.505.396-1.132.847-1.586 1.278c-.241.23-.664.254-.912.032a23 23 0 0 0-2.077-1.597c-4.313-2.918-12.162.929-8.814 9.14c1.214 3.645 6.947 8.802 10.409 10.775");
}

.rm9i_1rpx {
  fill-rule: evenodd;
  d: path("M7.17 6.551a4.3 4.3 0 0 0-1.506 1.205a.6.6 0 0 1-.93-.758a5.5 5.5 0 0 1 1.924-1.531c.943-.446 2.178-.688 3.774-.44a.6.6 0 0 1-.184 1.185c-1.373-.213-2.364.002-3.077.34");
}

.rumepbbob {
  stroke-linecap: round;
  stroke-opacity: 0.6;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M2.564 6.377c.297-.385 2.719-3.562 7.938-3.281");
}

.t5fy_6xue {
  fill-rule: evenodd;
  d: path("M24.83 6.551c.719.34 1.195.824 1.506 1.205a.6.6 0 0 0 .93-.758a5.5 5.5 0 0 0-1.924-1.531c-.942-.446-2.178-.688-3.774-.44a.6.6 0 0 0 .184 1.185c1.373-.213 2.364.002 3.077.34");
}

.um5epfuly {
  stop-color: var(--svg-color--9c1036, #9C1036);
}

.vgsv-4bxn {
  stop-color: var(--svg-color--ce2654, #CE2654);
}

.wj1z9qbob {
  fill-rule: evenodd;
  d: path("M20.548 4.03c5.208-.941 7.721 2.02 8.358 2.801a.6.6 0 1 0 .93-.758c-.738-.906-3.647-4.282-9.501-3.224a.6.6 0 1 0 .213 1.181");
}

.xg2pw8btp {
  stop-color: var(--svg-color--ff3b79, #FF3B79);
}

.xytj_udyc {
  stroke-linecap: round;
  stroke-opacity: 0.5;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M5.142 7.205c.297-.385 2-2.273 5.094-1.742");
}

.yw57-9naf {
  stop-color: var(--svg-color--ffbce6, #FFBCE6);
}

.yxx9jebfv {
  stop-color: var(--svg-color--b5286e, #B5286E);
}

.z55bs73lq {
  fill: var(--svg-color--fa1c56, #FA1C56);
  d: path("M16.983 13.788v4.174c0 2.714 2.846 3.58 3.54.956c.434-1.634.552-3.325.084-4.832c-.347-1.116-1.143-1.77-1.934-2.05c-1.013-.36-1.69.677-1.69 1.752");
}

.zvgzaacyw {
  cx: 24.063px;
  cy: 13.094px;
  rx: 3.616px;
  ry: 2.488px;
}

</style>
