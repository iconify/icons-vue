<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="t1rile24w"/><path fill="url(#iHbFlKe)" class="rf_y3-bdp"/><path fill="url(#iaV9eld)" class="rf_y3-bdp"/><path fill="url(#i2sVRvb)" class="rf_y3-bdp"/><path fill="url(#iSY3Ghc)" class="rf_y3-bdp"/><path fill="url(#iE6OBjb)" class="rf_y3-bdp"/><g filter="url(#iZELayc)"><path stroke="url(#iz2ZjEd)" class="lxk-3tpqc"/></g><g filter="url(#iMJm91d)"><path stroke="url(#i4NCN3d)" class="vvmjlibjj"/></g><g filter="url(#i0yHjPe)"><path stroke="url(#itU7xEc)" class="zc2fvpajr"/></g><g filter="url(#iZPA2nV)"><path class="nd3k8lbqa"/><path class="t8s3e72ba"/></g><g filter="url(#iqdGnXd)"><path class="yhveo764u"/><path class="f-wnd-d4p"/></g><g filter="url(#iuD34xc)"><path class="z2b6kowum"/><path class="js1_mbbyy"/></g><defs><filter id="iZELayc" width="15.185" height="15.478" x="4.573" y="4.264" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31065" stdDeviation=".5"/></filter><filter id="iMJm91d" width="15.185" height="15.478" x="12.5" y="12.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31065" stdDeviation=".5"/></filter><filter id="i0yHjPe" width="19.576" height="19.666" x="6.745" y="5.952" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31065" stdDeviation=".5"/></filter><filter id="iZPA2nV" width="18.435" height="18.435" x="6.783" y="6.782" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31065" stdDeviation=".5"/></filter><filter id="iqdGnXd" width="13.13" height="13.137" x="5.41" y="5.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31065" stdDeviation=".5"/></filter><filter id="iuD34xc" width="13.13" height="13.13" x="13.47" y="13.47" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31065" stdDeviation=".5"/></filter><radialGradient id="iHbFlKe" cx="0" cy="0" r="1" gradientTransform="rotate(140.932 10.014 9.358)scale(20.5276)" gradientUnits="userSpaceOnUse"><stop class="qp-snfmkn"/><stop offset="1" class="fzt2rvbkz"/></radialGradient><radialGradient id="iaV9eld" cx="0" cy="0" r="1" gradientTransform="rotate(-152.513 11.707 5.615)scale(20.854)" gradientUnits="userSpaceOnUse"><stop class="z6gonrb-o"/><stop offset=".503" class="z6gonrb-o"/><stop offset=".691" class="fa28nuluq"/><stop offset=".808" class="ucovmzbmv"/></radialGradient><radialGradient id="i2sVRvb" cx="0" cy="0" r="1" gradientTransform="rotate(93.031 2.683 13.882)scale(21.2798 22.657)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="q0p52ybuk"/><stop offset=".791" class="ycil9z-ax"/><stop offset=".842" class="w1hkfwb0i"/></radialGradient><radialGradient id="iSY3Ghc" cx="0" cy="0" r="1" gradientTransform="matrix(19.93748 -12.06249 19.32338 31.93863 8.375 20.375)" gradientUnits="userSpaceOnUse"><stop offset=".701" class="oeg7wubda"/><stop offset=".816" class="poi79qblf"/><stop offset=".989" class="fg--zm52a"/></radialGradient><radialGradient id="iE6OBjb" cx="0" cy="0" r="1" gradientTransform="rotate(-35.698 39.042 2.825)scale(31.169 21.2535)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="kgmjch99q"/><stop offset=".869" class="m0x_upb1l"/></radialGradient><linearGradient id="iz2ZjEd" x1="18.594" x2="13.15" y1="6.406" y2="20.594" gradientUnits="userSpaceOnUse"><stop class="z036u7bhl"/><stop offset=".125" class="z1vy_tbck"/><stop offset=".914" class="r068yybhv"/><stop offset=".976" class="zzcucvtxx"/></linearGradient><linearGradient id="i4NCN3d" x1="26.521" x2="21.077" y1="14.642" y2="28.83" gradientUnits="userSpaceOnUse"><stop class="z036u7bhl"/><stop offset=".125" class="z1vy_tbck"/><stop offset=".914" class="r068yybhv"/><stop offset=".976" class="zzcucvtxx"/></linearGradient><linearGradient id="itU7xEc" x1="24.125" x2="17.592" y1="8.734" y2="26.81" gradientUnits="userSpaceOnUse"><stop class="qr4qrn-ff"/><stop offset=".125" class="rrvrilc4n"/><stop offset=".954" class="bxxw7cekf"/><stop offset="1" class="zzcucvtxx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:flatbread" /></template>
<style>
.bxxw7cekf {
  stop-color: var(--svg-color--fbb78f, #FBB78F);
}

.f-wnd-d4p {
  stroke: var(--svg-color--ffbc9c, #FFBC9C);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("m6.655 17.105l.179.18c.26.27.682.27.951 0l9.51-9.51a.68.68 0 0 0 0-.95l-.18-.18a.68.68 0 0 0-.95 0l-9.51 9.51a.68.68 0 0 0 0 .95Z");
}

.fa28nuluq {
  stop-color: var(--svg-color--f4b28a, #F4B28A);
}

.fg--zm52a {
  stop-color: var(--svg-color--fff2bd, #FFF2BD);
}

.ft5dv1b6b {
  fill: none;
}

.fzt2rvbkz {
  stop-color: var(--svg-color--f4b28a, #F4B28A);
  stop-opacity: 0;
}

.js1_mbbyy {
  stroke: var(--svg-color--ffbc9c, #FFBC9C);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("m15.845 25.356l9.51-9.51a.68.68 0 0 0 0-.951l-.18-.18a.68.68 0 0 0-.95 0l-9.51 9.51a.68.68 0 0 0 0 .95l.18.18c.26.26.68.26.95.001Z");
}

.kgmjch99q {
  stop-color: var(--svg-color--ffd9a6, #FFD9A6);
  stop-opacity: 0;
}

.lxk-3tpqc {
  d: path("M6.125 16.688c-.187.468.172 1.015.422 1.265c.312.313 1.125.406 1.422.11c.125-.125 6.49-6.584 9.843-9.75c.513-.484.594-1.735.188-2.141c-.276-.328-1.25-.653-1.75-.14");
}

.m0x_upb1l {
  stop-color: var(--svg-color--f6d298, #F6D298);
}

.nd3k8lbqa {
  fill: var(--svg-color--eaa27f, #EAA27F);
  d: path("M8.1 23.9a.754.754 0 0 1 0-1.06L22.84 8.1c.29-.29.77-.29 1.06 0s.29.77 0 1.06L9.16 23.9c-.29.29-.77.29-1.06 0");
}

.oeg7wubda {
  stop-color: var(--svg-color--ffe0b9, #FFE0B9);
  stop-opacity: 0;
}

.poi79qblf {
  stop-color: var(--svg-color--ffdeb9, #FFDEB9);
}

.q0p52ybuk {
  stop-color: var(--svg-color--feb1b2, #FEB1B2);
  stop-opacity: 0;
}

.qp-snfmkn {
  stop-color: var(--svg-color--ffdbb8, #FFDBB8);
}

.qr4qrn-ff {
  stop-color: var(--svg-color--ffd4ad, #FFD4AD);
}

.r068yybhv {
  stop-color: var(--svg-color--f5b388, #F5B388);
}

.rf_y3-bdp {
  d: path("M30 16c0 8.938-6.268 14-14 14c-8.969 0-14-6.268-14-14C2 7.063 8.268 2 16 2s14 4.875 14 14");
}

.rrvrilc4n {
  stop-color: var(--svg-color--fec49b, #FEC49B);
}

.t1rile24w {
  fill: var(--svg-color--ffd1b1, #FFD1B1);
  d: path("M30 16c0 8.938-6.268 14-14 14c-8.969 0-14-6.268-14-14C2 7.063 8.268 2 16 2s14 4.875 14 14");
}

.t8s3e72ba {
  stroke: var(--svg-color--ffbc9c, #FFBC9C);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M8.065 22.805a.804.804 0 0 0 0 1.13c.31.31.82.31 1.13 0l14.74-14.74a.805.805 0 0 0 0-1.13a.804.804 0 0 0-1.13 0z");
}

.ucovmzbmv {
  stop-color: var(--svg-color--c99c7a, #C99C7A);
}

.vvmjlibjj {
  d: path("M14.052 24.924c-.187.468.172 1.015.422 1.265c.313.313 1.125.406 1.422.11c.125-.125 6.49-6.584 9.844-9.75c.512-.484.593-1.735.187-2.141c-.276-.328-1.25-.653-1.75-.14");
}

.w1hkfwb0i {
  stop-color: var(--svg-color--cc83ae, #CC83AE);
}

.ycil9z-ax {
  stop-color: var(--svg-color--ef9f9e, #EF9F9E);
}

.yhveo764u {
  fill: var(--svg-color--eaa27f, #EAA27F);
  d: path("m6.87 17.25l-.18-.18a.63.63 0 0 1 0-.88l9.51-9.51c.24-.24.64-.24.88 0l.18.18c.24.24.24.64 0 .88l-9.51 9.51a.61.61 0 0 1-.88 0");
}

.z036u7bhl {
  stop-color: var(--svg-color--ffc8a3, #FFC8A3);
}

.z1vy_tbck {
  stop-color: var(--svg-color--f8b991, #F8B991);
}

.z2b6kowum {
  fill: var(--svg-color--eaa27f, #EAA27F);
  d: path("m14.93 25.32l-.18-.18a.63.63 0 0 1 0-.88l9.51-9.51c.24-.24.64-.24.88 0l.18.18c.24.24.24.64 0 .88l-9.51 9.51c-.25.24-.64.24-.88 0");
}

.z6gonrb-o {
  stop-color: var(--svg-color--f9b68f, #F9B68F);
  stop-opacity: 0;
}

.zc2fvpajr {
  d: path("M8.297 22.562c-.188.47.172 1.016.422 1.266c.312.312 1.125.406 1.422.11c.125-.126 10.88-10.771 14.234-13.938c.512-.484.594-1.735.188-2.14c-.276-.329-1.25-.654-1.75-.141");
}

.zzcucvtxx {
  stop-color: var(--svg-color--ffd0b5, #FFD0B5);
}

</style>
