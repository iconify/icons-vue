<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect class="nvgif52ar"/><rect fill="url(#ilS03zc)" class="xy9miccfg"/><rect fill="url(#iEXs1jc)" class="xy9miccfg"/><rect fill="url(#iteCjDd)" class="xy9miccfg"/><rect fill="url(#iTKToyc)" class="xy9miccfg"/><rect fill="url(#ibVlAUb)" class="xy9miccfg"/><g filter="url(#iqwcxMd)"><path fill="url(#itZWqzb)" class="cpq57fbaj"/><path fill="url(#i2G40vb)" class="cpq57fbaj"/><path fill="url(#irLaK6c)" class="cpq57fbaj"/><path fill="url(#ivgOnSd)" class="cpq57fbaj"/><path fill="url(#i4Eg1Jg)" class="cpq57fbaj"/><path fill="url(#i342YLd)" class="cpq57fbaj"/><path fill="url(#iQr0cde)" class="cpq57fbaj"/><path fill="url(#ihcQZFb)" class="cpq57fbaj"/><path fill="url(#ik6JXwe)" class="cpq57fbaj"/><path fill="url(#iRwEzMb)" class="cpq57fbaj"/><path fill="url(#iCVUJVd)" class="cbalck9ze"/></g><g filter="url(#in6Sa6b)"><path fill="url(#iEu6eRc)" class="i0adfxbei"/></g><g filter="url(#ixscSyc)"><path fill="url(#itYxWej)" transform="matrix(-1 0 0 1 16.28 24.958)" class="hjhnqo9hj"/></g><g filter="url(#ikuSVjc)"><ellipse fill="url(#iSMzQHc)" transform="rotate(-12.48 22.684 11.886)" class="s40oc9nsq"/></g><g filter="url(#iYoJshd)"><ellipse fill="url(#iFAEDvc)" transform="rotate(-7.463 17.565 5.901)" class="dx6a8ccaw"/></g><g filter="url(#iWscsBe)"><ellipse fill="url(#iwgkjZG)" transform="rotate(-12.48 23.7 18.775)" class="dng7f_xde"/></g><g filter="url(#iVPEDqP)"><path stroke="url(#i0SKjVd)" class="xjayz2b9y"/></g><g filter="url(#i5FbkHx)"><path stroke="url(#iUQ5keI)" class="z3ctbybnw"/></g><g filter="url(#iNYCKcc)"><path stroke="url(#iIh1GeZ)" class="uwobs7bnx"/></g><g filter="url(#ic7KSQd)"><path stroke="url(#iHHYfBe)" class="h7y--jxmj"/></g><g filter="url(#i8pQOgb)"><path stroke="url(#iKaoure)" class="vvi6z7c4g"/></g><defs><radialGradient id="ibVlAUb" cx="0" cy="0" r="1" gradientTransform="matrix(.01562 2.15625 -.79706 .00577 17.556 24.676)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="a514u43hl"/><stop offset="1" class="lrw4rsbxq"/></radialGradient><radialGradient id="itZWqzb" cx="0" cy="0" r="1" gradientTransform="matrix(-16.5625 0 0 -16.7118 23.883 15.583)" gradientUnits="userSpaceOnUse"><stop class="ce2dyybra"/><stop offset="1" class="r395wmbbb"/></radialGradient><radialGradient id="i2G40vb" cx="0" cy="0" r="1" gradientTransform="matrix(8.5625 -3.8125 4.2446 9.53293 6.945 23.27)" gradientUnits="userSpaceOnUse"><stop class="ol9r14bpe"/><stop offset="1" class="ss_koxbkb"/></radialGradient><radialGradient id="irLaK6c" cx="0" cy="0" r="1" gradientTransform="matrix(9 0 0 6.69653 5.32 13.376)" gradientUnits="userSpaceOnUse"><stop class="ol9r14bpe"/><stop offset="1" class="ss_koxbkb"/></radialGradient><radialGradient id="ivgOnSd" cx="0" cy="0" r="1" gradientTransform="matrix(6.125 2.9375 -2.24944 4.69032 10.57 4.583)" gradientUnits="userSpaceOnUse"><stop class="ol9r14bpe"/><stop offset="1" class="ss_koxbkb"/></radialGradient><radialGradient id="i4Eg1Jg" cx="0" cy="0" r="1" gradientTransform="matrix(-2.125 .78126 -.32301 -.87858 9.977 7.24)" gradientUnits="userSpaceOnUse"><stop class="ol9r14bpe"/><stop offset="1" class="ss_koxbkb"/></radialGradient><radialGradient id="i342YLd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.3125 1.23023 -1.27947 -6.5652 25.883 12.145)" gradientUnits="userSpaceOnUse"><stop class="fawtpunrw"/><stop offset="1" class="h8632ubij"/></radialGradient><radialGradient id="iQr0cde" cx="0" cy="0" r="1" gradientTransform="matrix(-8.81248 -1.93755 2.01511 -9.16526 28.57 19.583)" gradientUnits="userSpaceOnUse"><stop class="fawtpunrw"/><stop offset="1" class="h8632ubij"/></radialGradient><radialGradient id="ihcQZFb" cx="0" cy="0" r="1" gradientTransform="rotate(156.009 11.117 4.267)scale(7.68592 8.09726)" gradientUnits="userSpaceOnUse"><stop class="fawtpunrw"/><stop offset="1" class="h8632ubij"/></radialGradient><radialGradient id="ik6JXwe" cx="0" cy="0" r="1" gradientTransform="matrix(12.75001 -1.43758 .75872 6.72916 8.32 26.96)" gradientUnits="userSpaceOnUse"><stop class="hgdz7jbjl"/><stop offset="1" class="aly83feqf"/></radialGradient><radialGradient id="iCVUJVd" cx="0" cy="0" r="1" gradientTransform="matrix(7.78511 0 0 3.07216 13.47 14.136)" gradientUnits="userSpaceOnUse"><stop class="zvez8jb6n"/><stop offset=".834" class="l_0au16xk"/></radialGradient><radialGradient id="iSMzQHc" cx="0" cy="0" r="1" gradientTransform="rotate(159.193 11.072 7.964)scale(4.53937 3.15303)" gradientUnits="userSpaceOnUse"><stop class="ihzwkeb_l"/><stop offset="1" class="ttzh-tuft"/></radialGradient><radialGradient id="iFAEDvc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.32954 1.29234 -.55495 -1.85918 19.992 5.457)" gradientUnits="userSpaceOnUse"><stop class="ihzwkeb_l"/><stop offset="1" class="ttzh-tuft"/></radialGradient><radialGradient id="iwgkjZG" cx="0" cy="0" r="1" gradientTransform="rotate(159.193 10.948 11.502)scale(4.53937 3.15303)" gradientUnits="userSpaceOnUse"><stop class="ihzwkeb_l"/><stop offset="1" class="ttzh-tuft"/></radialGradient><linearGradient id="ilS03zc" x1="13.098" x2="15.536" y1="28.302" y2="28.302" gradientUnits="userSpaceOnUse"><stop class="ino8s8bhe"/><stop offset="1" class="tihxfwbbz"/></linearGradient><linearGradient id="iEXs1jc" x1="13.698" x2="14.395" y1="27.732" y2="27.732" gradientUnits="userSpaceOnUse"><stop class="sum3fb1ai"/><stop offset="1" class="vgbtc0bcl"/></linearGradient><linearGradient id="iteCjDd" x1="15.986" x2="15.986" y1="30.133" y2="29.734" gradientUnits="userSpaceOnUse"><stop class="byk4aubip"/><stop offset="1" class="tqjxkxbtz"/></linearGradient><linearGradient id="iTKToyc" x1="18.789" x2="17.898" y1="26.708" y2="26.708" gradientUnits="userSpaceOnUse"><stop class="wf9374zcm"/><stop offset="1" class="kkzrpibam"/></linearGradient><linearGradient id="iRwEzMb" x1="11.694" x2="11.821" y1="25.306" y2="23.359" gradientUnits="userSpaceOnUse"><stop class="pey3d2bqz"/><stop offset="1" class="zpu3--blu"/></linearGradient><linearGradient id="iEu6eRc" x1="16.948" x2="16.948" y1="22.192" y2="29.852" gradientUnits="userSpaceOnUse"><stop class="gu041ebvi"/><stop offset="1" class="oukv3uckq"/></linearGradient><linearGradient id="itYxWej" x1=".372" x2=".372" y1="-1.044" y2="4.894" gradientUnits="userSpaceOnUse"><stop class="h_y25ewew"/><stop offset="1" class="i1w4b5baj"/></linearGradient><linearGradient id="i0SKjVd" x1="25.695" x2="9.383" y1="15.583" y2="15.583" gradientUnits="userSpaceOnUse"><stop offset=".092" class="ftha5rbfw"/><stop offset="1" class="q_idsureh"/></linearGradient><linearGradient id="iUQ5keI" x1="21.11" x2="8.82" y1="8.833" y2="8.833" gradientUnits="userSpaceOnUse"><stop class="ftha5rbfw"/><stop offset=".505" class="q_idsureh"/><stop offset="1" class="dcy8p2blk"/></linearGradient><linearGradient id="iIh1GeZ" x1="12.532" x2="16.893" y1="7.439" y2="-.493" gradientUnits="userSpaceOnUse"><stop class="ev_k34eba"/><stop offset="1" class="h_2utcbek"/></linearGradient><linearGradient id="iHHYfBe" x1="7.775" x2="15.841" y1="15.139" y2="4.782" gradientUnits="userSpaceOnUse"><stop class="ev_k34eba"/><stop offset="1" class="h_2utcbek"/></linearGradient><linearGradient id="iKaoure" x1="6.383" x2="3.598" y1="16.583" y2="23.346" gradientUnits="userSpaceOnUse"><stop class="ev_k34eba"/><stop offset="1" class="h_2utcbek"/></linearGradient><filter id="iqwcxMd" width="23.317" height="22.613" x="4.577" y="2.069" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.72549 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7673"/></filter><filter id="in6Sa6b" width="3.334" height="6.894" x="15.281" y="23.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7673" stdDeviation=".5"/></filter><filter id="ixscSyc" width="2.745" height="6.894" x="14.536" y="23.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7673" stdDeviation=".5"/></filter><filter id="ikuSVjc" width="9.335" height="8.972" x="18.016" y="7.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7673" stdDeviation="1"/></filter><filter id="iYoJshd" width="9.121" height="8.052" x="13.004" y="1.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7673" stdDeviation="1"/></filter><filter id="iWscsBe" width="9.335" height="8.972" x="19.032" y="14.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7673" stdDeviation="1"/></filter><filter id="iVPEDqP" width="17.019" height="2.284" x="8.483" y="14.199" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7673" stdDeviation=".325"/></filter><filter id="i5FbkHx" width="10.909" height="2.55" x="10.545" y="6.933" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7673" stdDeviation=".225"/></filter><filter id="iNYCKcc" width="5.125" height="6.953" x="10.505" y="1.88" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7673" stdDeviation=".5"/></filter><filter id="ic7KSQd" width="5.985" height="10.173" x="5.392" y="6.698" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7673" stdDeviation=".625"/></filter><filter id="i8pQOgb" width="5.719" height="11.28" x="3.983" y="13.745" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7673" stdDeviation=".625"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:deciduous-tree" /></template>
<style>
.a514u43hl {
  stop-color: var(--svg-color--4d2d31, #4D2D31);
}

.aly83feqf {
  stop-color: var(--svg-color--5a6f6c, #5A6F6C);
  stop-opacity: 0;
}

.byk4aubip {
  stop-color: var(--svg-color--6a2f5b, #6A2F5B);
}

.cbalck9ze {
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("M21.22 7.327a.18.18 0 0 1-.165-.181a5.077 5.077 0 1 0-10.154 0a.184.184 0 0 1-.165.183a5.274 5.274 0 0 0-4.217 7.523a.45.45 0 0 1-.11.53a5.295 5.295 0 0 0 3.463 9.3H22.1a5.295 5.295 0 0 0 3.463-9.3a.45.45 0 0 1-.11-.53a5.274 5.274 0 0 0-4.234-7.525");
}

.ce2dyybra {
  stop-color: var(--svg-color--7cbe4d, #7CBE4D);
}

.cpq57fbaj {
  d: path("M21.22 7.327a.18.18 0 0 1-.165-.181a5.077 5.077 0 1 0-10.154 0a.184.184 0 0 1-.165.183a5.274 5.274 0 0 0-4.217 7.523a.45.45 0 0 1-.11.53a5.295 5.295 0 0 0 3.463 9.3H22.1a5.295 5.295 0 0 0 3.463-9.3a.45.45 0 0 1-.11-.53a5.274 5.274 0 0 0-4.234-7.525");
}

.dcy8p2blk {
  stop-color: var(--svg-color--6ca663, #6CA663);
}

.dng7f_xde {
  cx: 23.699px;
  cy: 18.775px;
  rx: 2.676px;
  ry: 2.476px;
}

.dx6a8ccaw {
  cx: 17.565px;
  cy: 5.901px;
  rx: 2.569px;
  ry: 2.015px;
}

.ev_k34eba {
  stop-color: var(--svg-color--8fb48e, #8FB48E);
}

.fawtpunrw {
  stop-color: var(--svg-color--81cb44, #81CB44);
}

.ft5dv1b6b {
  fill: none;
}

.ftha5rbfw {
  stop-color: var(--svg-color--9ddb71, #9DDB71);
}

.gu041ebvi {
  stop-color: var(--svg-color--7f5b60, #7F5B60);
  stop-opacity: 0;
}

.h_2utcbek {
  stop-color: var(--svg-color--8fb48e, #8FB48E);
  stop-opacity: 0;
}

.h_y25ewew {
  stop-color: var(--svg-color--683b4b, #683B4B);
  stop-opacity: 0;
}

.h7y--jxmj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.877 8.198c-.81.231-2.528 1.22-2.907 3.318c-.298 1.646.326 3.444.727 3.855");
}

.h8632ubij {
  stop-color: var(--svg-color--81cb44, #81CB44);
  stop-opacity: 0;
}

.hgdz7jbjl {
  stop-color: var(--svg-color--5a6f6c, #5A6F6C);
}

.hjhnqo9hj {
  d: path("M0 0h.745v4.894H0z");
}

.i0adfxbei {
  d: path("M16.281 24.958h1.334v4.894h-1.334z");
}

.i1w4b5baj {
  stop-color: var(--svg-color--683b4b, #683B4B);
}

.ihzwkeb_l {
  stop-color: var(--svg-color--a0e271, #A0E271);
}

.ino8s8bhe {
  stop-color: var(--svg-color--908181, #908181);
}

.kkzrpibam {
  stop-color: var(--svg-color--6d5c5c, #6D5C5C);
  stop-opacity: 0;
}

.l_0au16xk {
  stop-color: var(--svg-color--5b8f67, #5B8F67);
  stop-opacity: 0;
}

.lrw4rsbxq {
  stop-color: var(--svg-color--4d2d31, #4D2D31);
  stop-opacity: 0;
}

.nvgif52ar {
  width: 4.575px;
  height: 8.362px;
  x: 13.698px;
  y: 21.77px;
  fill: var(--svg-color--5b363a, #5B363A);
  rx: 0.25px;
}

.ol9r14bpe {
  stop-color: var(--svg-color--438154, #438154);
}

.oukv3uckq {
  stop-color: var(--svg-color--7f5b60, #7F5B60);
}

.pey3d2bqz {
  stop-color: var(--svg-color--7a7397, #7A7397);
}

.q_idsureh {
  stop-color: var(--svg-color--6ca663, #6CA663);
  stop-opacity: 0;
}

.r395wmbbb {
  stop-color: var(--svg-color--549756, #549756);
}

.s40oc9nsq {
  cx: 22.684px;
  cy: 11.886px;
  rx: 2.676px;
  ry: 2.476px;
}

.ss_koxbkb {
  stop-color: var(--svg-color--438154, #438154);
  stop-opacity: 0;
}

.sum3fb1ai {
  stop-color: var(--svg-color--5b363a, #5B363A);
}

.tihxfwbbz {
  stop-color: var(--svg-color--908181, #908181);
  stop-opacity: 0;
}

.tqjxkxbtz {
  stop-color: var(--svg-color--6a2f5b, #6A2F5B);
  stop-opacity: 0;
}

.ttzh-tuft {
  stop-color: var(--svg-color--a0e271, #A0E271);
  stop-opacity: 0;
}

.uwobs7bnx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M14.38 3.13c-.864.323-2.625 1.353-2.625 4.453");
}

.vgbtc0bcl {
  stop-color: var(--svg-color--5b363a, #5B363A);
  stop-opacity: 0;
}

.vvi6z7c4g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M7.634 15.245c-.738.39-2.2 1.763-2.15 4.14s1.834 3.75 2.718 4.14");
}

.wf9374zcm {
  stop-color: var(--svg-color--6d5c5c, #6D5C5C);
}

.xjayz2b9y {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.383 15.583h10.875c1-.016 3.269-.134 4.344-.484");
}

.xy9miccfg {
  width: 4.575px;
  height: 8.362px;
  x: 13.698px;
  y: 21.77px;
  rx: 0.25px;
}

.z3ctbybnw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.195 7.583c.677.417 2.575 1.25 4.75 1.25s4.266-.833 4.86-1.25");
}

.zpu3--blu {
  stop-color: var(--svg-color--7a7397, #7A7397);
  stop-opacity: 0;
}

.zvez8jb6n {
  stop-color: var(--svg-color--5b8f67, #5B8F67);
}

</style>
