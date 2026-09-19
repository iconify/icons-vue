<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iU9z4At)"><path fill="url(#iAInZhz)" class="enh5k8fqc"/><path fill="url(#iXG6gBe)" class="enh5k8fqc"/><path fill="url(#i82kOHb)" class="enh5k8fqc"/><path fill="url(#iWyordK)" class="enh5k8fqc"/><path fill="url(#i78uWPe)" class="enh5k8fqc"/></g><path fill="url(#i7XRtmc)" class="enh5k8fqc"/><path fill="url(#i6B764b)" class="enh5k8fqc"/><rect fill="url(#i6tBc8d)" class="a1yscj3wv"/><rect fill="url(#iXUAWjN)" class="a1yscj3wv"/><rect fill="url(#iZNo5ab)" class="a1yscj3wv"/><rect fill="url(#ictxqbb)" class="a1yscj3wv"/><path fill="url(#iVE51dd)" class="ka0uvzcrk"/><path fill="url(#izoqt5c)" class="ka0uvzcrk"/><path fill="url(#iSjHD8x)" class="ka0uvzcrk"/><g filter="url(#i6tdHHd)"><rect fill="url(#i2oXlIL)" class="zl_vf-2-e"/></g><g filter="url(#iavhnjd)"><rect fill="url(#i0CaxOb)" transform="rotate(51.914 16.04 4.072)" class="d7pevmjlk"/></g><g filter="url(#imM5Znd)"><rect fill="url(#imk4Pye)" class="rgczqabmh"/></g><g filter="url(#iKX7G6c)"><rect fill="url(#ijTIAFd)" class="i7z28tb1l"/></g><g filter="url(#itkUvfe)"><rect fill="url(#iwoQMEe)" class="k4s4h0qfu"/></g><path fill="url(#iQbDZvc)" class="u302-2b6e"/><defs><linearGradient id="i6B764b" x1="17.67" x2="17.67" y1="29.444" y2="26.277" gradientUnits="userSpaceOnUse"><stop offset=".113" class="sf1_yi9uz"/><stop offset="1" class="r8_0955bc"/></linearGradient><linearGradient id="i6tBc8d" x1="7.151" x2="7.151" y1="16.163" y2="13.7" gradientUnits="userSpaceOnUse"><stop class="lsb4y9brj"/><stop offset="1" class="wxku3y25c"/></linearGradient><linearGradient id="iZNo5ab" x1="9.029" x2="9.029" y1="9.951" y2="14.081" gradientUnits="userSpaceOnUse"><stop class="dxu3_d96v"/><stop offset="1" class="dknqvcbnm"/></linearGradient><linearGradient id="ictxqbb" x1="16.04" x2="9.462" y1="14.154" y2="14.154" gradientUnits="userSpaceOnUse"><stop class="tug9qbcrz"/><stop offset="1" class="ob4a_q12l"/></linearGradient><linearGradient id="iVE51dd" x1="20.153" x2="17.653" y1="6.134" y2="8.509" gradientUnits="userSpaceOnUse"><stop class="onfboeb4a"/><stop offset="1" class="j4_znybcj"/></linearGradient><linearGradient id="izoqt5c" x1="22.276" x2="20.166" y1="10.109" y2="8.047" gradientUnits="userSpaceOnUse"><stop offset=".223" class="gx7uucbtd"/><stop offset="1" class="mz7q0cbua"/></linearGradient><linearGradient id="iSjHD8x" x1="13.872" x2="16.61" y1="9.102" y2="7.237" gradientUnits="userSpaceOnUse"><stop offset=".05" class="xt1r2qb6l"/><stop offset="1" class="y7q-z5_xl"/></linearGradient><linearGradient id="i2oXlIL" x1="7.761" x2="19.953" y1="13.154" y2="13.154" gradientUnits="userSpaceOnUse"><stop class="d8wcvj4ci"/><stop offset="1" class="n2gu5ehbv"/></linearGradient><linearGradient id="i0CaxOb" x1="20.572" x2="20.801" y1="4.084" y2="6.729" gradientUnits="userSpaceOnUse"><stop class="kx8y3lbba"/><stop offset="1" class="om06n0lcb"/></linearGradient><linearGradient id="imk4Pye" x1="8.585" x2="14.682" y1="15.225" y2="17.252" gradientUnits="userSpaceOnUse"><stop class="a9nr4qdli"/><stop offset="1" class="n9ezgj94a"/></linearGradient><linearGradient id="ijTIAFd" x1="9.105" x2="15.202" y1="19.785" y2="21.811" gradientUnits="userSpaceOnUse"><stop class="a9nr4qdli"/><stop offset="1" class="n9ezgj94a"/></linearGradient><linearGradient id="iwoQMEe" x1="10.357" x2="15.073" y1="23.944" y2="25.374" gradientUnits="userSpaceOnUse"><stop class="a9nr4qdli"/><stop offset="1" class="n9ezgj94a"/></linearGradient><radialGradient id="iAInZhz" cx="0" cy="0" r="1" gradientTransform="matrix(-12.16159 12.46549 -18.5232 -18.0716 25.943 15.555)" gradientUnits="userSpaceOnUse"><stop class="s3_a2ccir"/><stop offset="1" class="hpu5u8b1u"/></radialGradient><radialGradient id="iXG6gBe" cx="0" cy="0" r="1" gradientTransform="matrix(6.51954 0 0 1.95986 7.375 19.236)" gradientUnits="userSpaceOnUse"><stop class="vd81z2bcl"/><stop offset=".763" class="bk9kdye5u"/></radialGradient><radialGradient id="i82kOHb" cx="0" cy="0" r="1" gradientTransform="matrix(6.40568 0 0 1.97994 9.26 23.605)" gradientUnits="userSpaceOnUse"><stop class="m6vv2qbmd"/><stop offset=".763" class="jlx1fcb6a"/></radialGradient><radialGradient id="iWyordK" cx="0" cy="0" r="1" gradientTransform="matrix(2.6514 -.02425 .00282 .3086 9.27 19.79)" gradientUnits="userSpaceOnUse"><stop class="l37-eo69e"/><stop offset="1" class="cf78o4b4l"/></radialGradient><radialGradient id="i78uWPe" cx="0" cy="0" r="1" gradientTransform="matrix(2.375 0 0 .20313 10.169 24.259)" gradientUnits="userSpaceOnUse"><stop class="l37-eo69e"/><stop offset="1" class="cf78o4b4l"/></radialGradient><radialGradient id="i7XRtmc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.9779 2.23385 -3.86445 -10.34144 30.398 14.224)" gradientUnits="userSpaceOnUse"><stop class="r_tw_ub5a"/><stop offset="1" class="ph-1oee-a"/></radialGradient><radialGradient id="iXUAWjN" cx="0" cy="0" r="1" gradientTransform="matrix(-8.32112 0 0 -7.02379 10.554 12.588)" gradientUnits="userSpaceOnUse"><stop offset=".893" class="x2mb0acco"/><stop offset="1" class="doysnhfra"/></radialGradient><radialGradient id="iQbDZvc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.27976 1.21993 -.27629 -.7428 10.215 14.916)" gradientUnits="userSpaceOnUse"><stop class="w0e1q9b-c"/><stop offset="1" class="w5fga1bor"/></radialGradient><filter id="iU9z4At" width="27.964" height="26.287" x="2.018" y="2.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.568627 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2754"/></filter><filter id="i6tdHHd" width="16.315" height="5.12" x="2.462" y="9.296" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2754" stdDeviation=".75"/></filter><filter id="iavhnjd" width="9.457" height="10.641" x="13.272" y="3.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2754" stdDeviation=".75"/></filter><filter id="imM5Znd" width="6.885" height="4.65" x="7.93" y="14.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2754" stdDeviation=".5"/></filter><filter id="iKX7G6c" width="6.885" height="4.65" x="8.45" y="18.785" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2754" stdDeviation=".5"/></filter><filter id="itkUvfe" width="5.715" height="4.211" x="9.62" y="22.944" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2754" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:backhand-index-pointing-left-medium-light" /></template>
<style>
.a1yscj3wv {
  width: 14.022px;
  height: 5.274px;
  x: 2.018px;
  y: 9.951px;
  rx: 2.637px;
}

.a9nr4qdli {
  stop-color: var(--svg-color--e1ad8f, #E1AD8F);
}

.bk9kdye5u {
  stop-color: var(--svg-color--c17f77, #C17F77);
  stop-opacity: 0;
}

.cf78o4b4l {
  stop-color: var(--svg-color--bf7b60, #BF7B60);
  stop-opacity: 0;
}

.d7pevmjlk {
  width: 9.122px;
  height: 2.167px;
  x: 16.04px;
  y: 4.072px;
  rx: 1.083px;
}

.d8wcvj4ci {
  stop-color: var(--svg-color--eeba98, #EEBA98);
}

.dknqvcbnm {
  stop-color: var(--svg-color--dfb28c, #DFB28C);
  stop-opacity: 0;
}

.doysnhfra {
  stop-color: var(--svg-color--e2a788, #E2A788);
}

.dxu3_d96v {
  stop-color: var(--svg-color--dfb28c, #DFB28C);
}

.enh5k8fqc {
  d: path("M18.12 4.527c-.86-1.24-2.597-1.702-3.849-.889a2.657 2.657 0 0 0-.781 3.703l1.695 2.61H4.655a2.637 2.637 0 0 0 0 5.274h4.284a2.493 2.493 0 0 0 .344 4.564a2.724 2.724 0 0 0 .884 4.487a2.723 2.723 0 0 0 2.07 4.493h3.102l.104-.002h4.859c1.431 0 3.878-.849 6.022-2.51a9 9 0 0 0 .65-.537a9.2 9.2 0 0 0 3.008-6.833a9.2 9.2 0 0 0-3.944-7.577c-.833-.603-1.507-.892-2.176-1.178c-.513-.22-1.023-.439-1.601-.797c-.913-.566-1.59-1.4-1.969-1.865l-.08-.098v.002z");
}

.ft5dv1b6b {
  fill: none;
}

.gx7uucbtd {
  stop-color: var(--svg-color--efb79b, #EFB79B);
}

.hpu5u8b1u {
  stop-color: var(--svg-color--d79c8f, #D79C8F);
}

.i7z28tb1l {
  width: 4.885px;
  height: 2.65px;
  x: 9.45px;
  y: 19.785px;
  rx: 1.325px;
}

.j4_znybcj {
  stop-color: var(--svg-color--f9cba1, #F9CBA1);
  stop-opacity: 0;
}

.jlx1fcb6a {
  stop-color: var(--svg-color--c07d7c, #C07D7C);
  stop-opacity: 0;
}

.k4s4h0qfu {
  width: 3.715px;
  height: 2.211px;
  x: 10.62px;
  y: 23.944px;
  rx: 1.105px;
}

.ka0uvzcrk {
  d: path("M14.271 3.638c1.252-.813 2.988-.35 3.848.889l2.092 2.847v-.002l.078.094l.003.004c.378.466 1.056 1.299 1.969 1.865a9 9 0 0 0 1.185.616h-8.261l-1.695-2.61a2.657 2.657 0 0 1 .781-3.703");
}

.kx8y3lbba {
  stop-color: var(--svg-color--ffcea4, #FFCEA4);
}

.l37-eo69e {
  stop-color: var(--svg-color--bf7b60, #BF7B60);
}

.lsb4y9brj {
  stop-color: var(--svg-color--b87380, #B87380);
}

.m6vv2qbmd {
  stop-color: var(--svg-color--c07d7c, #C07D7C);
}

.mz7q0cbua {
  stop-color: var(--svg-color--efb79b, #EFB79B);
  stop-opacity: 0;
}

.n2gu5ehbv {
  stop-color: var(--svg-color--eeba98, #EEBA98);
  stop-opacity: 0;
}

.n9ezgj94a {
  stop-color: var(--svg-color--e1ad8f, #E1AD8F);
  stop-opacity: 0;
}

.ob4a_q12l {
  stop-color: var(--svg-color--edb59d, #EDB59D);
  stop-opacity: 0;
}

.om06n0lcb {
  stop-color: var(--svg-color--ffcea4, #FFCEA4);
  stop-opacity: 0;
}

.onfboeb4a {
  stop-color: var(--svg-color--f9cba1, #F9CBA1);
}

.ph-1oee-a {
  stop-color: var(--svg-color--ffd2aa, #FFD2AA);
  stop-opacity: 0;
}

.r_tw_ub5a {
  stop-color: var(--svg-color--ffd2aa, #FFD2AA);
}

.r8_0955bc {
  stop-color: var(--svg-color--bc778b, #BC778B);
  stop-opacity: 0;
}

.rgczqabmh {
  width: 4.885px;
  height: 2.65px;
  x: 8.93px;
  y: 15.225px;
  rx: 1.325px;
}

.s3_a2ccir {
  stop-color: var(--svg-color--fcc6a6, #FCC6A6);
}

.sf1_yi9uz {
  stop-color: var(--svg-color--bc778b, #BC778B);
}

.tug9qbcrz {
  stop-color: var(--svg-color--edb59d, #EDB59D);
}

.u302-2b6e {
  d: path("M7.612 17.596h6.423v-2.37H8.939a2.49 2.49 0 0 0-1.327 2.37");
}

.vd81z2bcl {
  stop-color: var(--svg-color--c17f77, #C17F77);
}

.w0e1q9b-c {
  stop-color: var(--svg-color--a36142, #A36142);
}

.w5fga1bor {
  stop-color: var(--svg-color--a36142, #A36142);
  stop-opacity: 0;
}

.wxku3y25c {
  stop-color: var(--svg-color--b87380, #B87380);
  stop-opacity: 0;
}

.x2mb0acco {
  stop-color: var(--svg-color--e2a788, #E2A788);
  stop-opacity: 0;
}

.xt1r2qb6l {
  stop-color: var(--svg-color--d29377, #D29377);
}

.y7q-z5_xl {
  stop-color: var(--svg-color--d29377, #D29377);
  stop-opacity: 0;
}

.zl_vf-2-e {
  width: 13.315px;
  height: 2.12px;
  x: 3.962px;
  y: 10.796px;
  rx: 1.06px;
}

</style>
