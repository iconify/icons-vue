<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><path fill="url(#i4i2ZRd)" clip-rule="evenodd" class="w9z6nqbqd"/><g filter="url(#ixE7SCb)"><path class="w2kdlfbqq"/></g><path stroke="url(#iWZXbeb)" class="lw7vm-bzl"/><g filter="url(#iGnaxBc)" class="ozarfyqlu"><path class="ut946vb5i"/></g><path stroke="url(#iKpinAd)" class="h3nl4hb0q"/><g filter="url(#imffeGd)" class="nctb2ac4r"><path class="p20bq15rh"/></g><path stroke="url(#iunUJuc)" class="awpawjbnq"/><g filter="url(#iyKQ3EY)" class="nctb2ac4r"><path class="s_57dbciy"/></g><path stroke="url(#iKUKqZd)" class="w7ph4kb1w"/><g filter="url(#iVN1j1c)"><path fill="url(#iQpLLPe)" clip-rule="evenodd" class="y-lxzwaix"/></g><path fill="url(#i1Zcdlb)" class="de-gd__ix"/><path fill="url(#il92Txd)" class="yxr0-1pyx"/><g filter="url(#iWw1pHc)"><path fill="url(#idjhBEc)" class="m1mdfiuel"/></g><path fill="url(#iwOpvPz)" clip-rule="evenodd" class="jrk487zjg"/><path fill="url(#iH1DOte)" class="wxltn3brk"/><path fill="url(#iKnQuRd)" class="d_wl458hb"/><g filter="url(#iCQmyEd)"><path fill="url(#iyXNP8b)" class="ezmi3sohu"/></g></g><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iWZXbeb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.5 -4.7996 0 10.5 10)" gradientUnits="userSpaceOnUse"><stop class="d-sg2f4zs"/><stop offset=".651" class="y2h4i9bfm"/><stop offset="1" class="hvts7mbyo"/></radialGradient><radialGradient id="iunUJuc" cx="0" cy="0" r="1" gradientTransform="matrix(1 -2 2.99896 1.49948 11.5 7)" gradientUnits="userSpaceOnUse"><stop class="dyun_0b6j"/><stop offset="1" class="d-sg2f4zs"/></radialGradient><radialGradient id="iKUKqZd" cx="0" cy="0" r="1" gradientTransform="matrix(-1 -2 2.99896 -1.49948 20.5 7)" gradientUnits="userSpaceOnUse"><stop class="dyun_0b6j"/><stop offset="1" class="d-sg2f4zs"/></radialGradient><radialGradient id="iQpLLPe" cx="0" cy="0" r="1" gradientTransform="matrix(5.31688 8 -15.75292 10.46954 7.183 22)" gradientUnits="userSpaceOnUse"><stop offset=".336" class="mtzd7obsz"/><stop offset="1" class="ot25-4i2p"/></radialGradient><radialGradient id="i1Zcdlb" cx="0" cy="0" r="1" gradientTransform="rotate(139.399 -.107 11.045)scale(4.60977)" gradientUnits="userSpaceOnUse"><stop class="b8rk2tvqp"/><stop offset=".91" class="mi35usbgl"/></radialGradient><radialGradient id="il92Txd" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 5.5 -5.5 -.5 12 24.5)" gradientUnits="userSpaceOnUse"><stop class="cwqrq8b-d"/><stop offset=".91" class="bb6cnobcn"/></radialGradient><radialGradient id="idjhBEc" cx="0" cy="0" r="1" gradientTransform="matrix(-8 8 -8 -8 9.5 22)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="xf3nhjbpw"/><stop offset=".741" class="l99ip2bsq"/></radialGradient><radialGradient id="iH1DOte" cx="0" cy="0" r="1" gradientTransform="rotate(135.003 10.462 15.756)scale(5.6572)" gradientUnits="userSpaceOnUse"><stop class="b8rk2tvqp"/><stop offset=".91" class="mi35usbgl"/></radialGradient><radialGradient id="iKnQuRd" cx="0" cy="0" r="1" gradientTransform="matrix(-2 6 -6 -2 21 23.5)" gradientUnits="userSpaceOnUse"><stop class="k_9w9kb3m"/><stop offset=".91" class="bb6cnobcn"/></radialGradient><radialGradient id="iyXNP8b" cx="0" cy="0" r="1" gradientTransform="matrix(-8 8 -8 -8 28.5 22)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="xf3nhjbpw"/><stop offset=".741" class="l99ip2bsq"/></radialGradient><filter id="ixE7SCb" width="10" height="6.52" x="5" y="9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1422" stdDeviation=".75"/></filter><filter id="iGnaxBc" width="9" height="5.52" x="16.5" y="9.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1422" stdDeviation=".5"/></filter><filter id="imffeGd" width="8" height="5.995" x="7.25" y="4.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1422" stdDeviation=".75"/></filter><filter id="iyKQ3EY" width="8.627" height="6.276" x="15.672" y="4.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1422" stdDeviation=".875"/></filter><filter id="iVN1j1c" width="12.501" height="13.501" x="2" y="15.999" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.745098 0 0 0 0 0.764706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_31_1422"/></filter><filter id="iWw1pHc" width="10.5" height="9.5" x="2" y="20" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.5" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.749966 0 0 0 0 0.634228 0 0 0 0 0.878564 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_31_1422"/></filter><filter id="iCQmyEd" width="10.5" height="9.5" x="21" y="20" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.5" dy=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.749966 0 0 0 0 0.634228 0 0 0 0 0.878564 0 0 0 0.8 0"/><feBlend in2="shape" result="effect1_innerShadow_31_1422"/></filter><linearGradient id="i4i2ZRd" x1="16" x2="16" y1="17.926" y2="19.989" gradientUnits="userSpaceOnUse"><stop class="da3dd5b9t"/><stop offset="1" class="nflylhbjg"/></linearGradient><linearGradient id="iKpinAd" x1="21.5" x2="21.038" y1="10.5" y2="12.912" gradientUnits="userSpaceOnUse"><stop class="d-sg2f4zs"/><stop offset="1" class="hvts7mbyo"/></linearGradient><linearGradient id="iwOpvPz" x1="26.5" x2="21.5" y1="19" y2="25" gradientUnits="userSpaceOnUse"><stop class="ls12e09pb"/><stop offset=".455" class="v_xfr5-0z"/><stop offset=".874" class="l5dh48xrf"/></linearGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:face-with-steam-from-nose" /></template>
<style>
.awpawjbnq {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.83c1.75-.83 3.537 0 4 1.67");
}

.b8rk2tvqp {
  stop-color: var(--svg-color--eeeaf9, #EEEAF9);
  stop-opacity: 0;
}

.bb6cnobcn {
  stop-color: var(--svg-color--ec94ff, #EC94FF);
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.cwqrq8b-d {
  stop-color: var(--svg-color--fae8ff, #FAE8FF);
  stop-opacity: 0;
}

.d_wl458hb {
  d: path("M22 29a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.d-sg2f4zs {
  stop-color: var(--svg-color--52383e, #52383E);
}

.da3dd5b9t {
  stop-color: var(--svg-color--4f3c43, #4F3C43);
}

.de-gd__ix {
  d: path("M5 24a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.dyun_0b6j {
  stop-color: var(--svg-color--301e26, #301E26);
}

.ezmi3sohu {
  d: path("M25.5 29a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9");
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

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.h3nl4hb0q {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 11c1 1.5 3.5 2 5 1");
}

.hvts7mbyo {
  stop-color: var(--svg-color--432a35, #432A35);
}

.jrk487zjg {
  fill-rule: evenodd;
  d: path("M27 24a3 3 0 1 0-2.547-4.585l-5.304-3.3c-.607-.376-1.348.228-1.1.898l2.377 6.433A3 3 0 1 0 24.83 25H27z");
}

.k_9w9kb3m {
  stop-color: var(--svg-color--c38eec, #C38EEC);
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.l5dh48xrf {
  stop-color: var(--svg-color--c28eec, #C28EEC);
}

.l99ip2bsq {
  stop-color: var(--svg-color--e88dff, #E88DFF);
}

.ls12e09pb {
  stop-color: var(--svg-color--fff8ff, #FFF8FF);
}

.lw7vm-bzl {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 11c-1 1.5-3.5 2-5 1");
}

.m1mdfiuel {
  d: path("M6.5 29a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9");
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mi35usbgl {
  stop-color: var(--svg-color--c39ed9, #C39ED9);
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.mtzd7obsz {
  stop-color: var(--svg-color--fef4ff, #FEF4FF);
}

.nctb2ac4r {
  opacity: var(--svg-opacity--0-8, 0.8);
}

.nflylhbjg {
  stop-color: var(--svg-color--512756, #512756);
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.ot25-4i2p {
  stop-color: var(--svg-color--f8b1ff, #F8B1FF);
}

.ozarfyqlu {
  opacity: var(--svg-opacity--0-7, 0.7);
}

.p20bq15rh {
  stroke: var(--svg-color--aa7013, #AA7013);
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.25 6.325c1.75-.83 3.537 0 4 1.67");
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.s_57dbciy {
  stroke: var(--svg-color--d59a25, #D59A25);
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.05 6.724c-1.673-.975-3.525-.3-4.127 1.325");
}

.ut946vb5i {
  stroke: var(--svg-color--f4b158, #F4B158);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.5 11.5c1 1.5 3.5 2 5 1");
}

.v_xfr5-0z {
  stop-color: var(--svg-color--d0c1db, #D0C1DB);
}

.w2kdlfbqq {
  stroke: var(--svg-color--ce7c25, #CE7C25);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.5 11.5c-1 1.5-3.5 2-5 1");
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.w7ph4kb1w {
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.5 5.83c-1.75-.83-3.538 0-4 1.67");
}

.w9z6nqbqd {
  fill-rule: evenodd;
  d: path("M20.246 21.7a6.007 6.007 0 0 0-8.488.026a1 1 0 0 1-1.416-1.412a8.007 8.007 0 0 1 11.312-.034a1 1 0 1 1-1.408 1.42");
}

.wxltn3brk {
  d: path("M27 24a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.xf3nhjbpw {
  stop-color: var(--svg-color--fff6ff, #FFF6FF);
}

.y-lxzwaix {
  fill-rule: evenodd;
  d: path("M5 24a3 3 0 1 1 2.548-4.585l5.304-3.3c.606-.376 1.347.228 1.1.898l-2.378 6.433A3 3 0 1 1 7.17 25H5z");
}

.y2h4i9bfm {
  stop-color: var(--svg-color--5c4553, #5C4553);
}

.yxr0-1pyx {
  d: path("M10 29a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

</style>
