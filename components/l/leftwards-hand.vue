<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#isU4kqb)"><path fill="url(#iDxwosV)" class="aspe13b4o"/><path fill="url(#iikJcHc)" class="aspe13b4o"/></g><path fill="url(#iwiYw2d)" class="aspe13b4o"/><path fill="url(#iacj7Or)" class="aspe13b4o"/><path fill="url(#iuEbdJc)" class="aspe13b4o"/><path fill="url(#iCskouc)" class="ldx0mbbzq"/><path fill="url(#iisrD8c)" class="ldx0mbbzq"/><path fill="url(#itNxYfd)" class="ldx0mbbzq"/><path fill="url(#iz6bate)" class="ldx0mbbzq"/><path fill="url(#i5aWGvc)" class="msizombgs"/><path fill="url(#iFoqw1Y)" class="msizombgs"/><path fill="url(#iPaPEGb)" class="msizombgs"/><path fill="url(#ibMQ2fc)" class="msizombgs"/><path fill="url(#izoudmd)" class="u978vfesz"/><path fill="url(#iDPo8Xc)" class="u978vfesz"/><path fill="url(#iaje8eb)" class="u978vfesz"/><path fill="url(#icdXzsx)" class="u978vfesz"/><path fill="url(#irMEq9f)" class="wq5e5tu3b"/><path fill="url(#ilRFbhC)" class="wq5e5tu3b"/><g filter="url(#iiDYNId)"><path fill="url(#i6kerhd)" class="deak9vbee"/></g><g filter="url(#iwVZ1Md)"><path fill="url(#i9Yr13w)" class="yei81-omf"/></g><g filter="url(#i78EpLv)"><path fill="url(#i1hJWGw)" class="s6bul9b5u"/></g><g filter="url(#iRaLund)"><path class="o6ivf5b4i"/></g><path fill="url(#iL4aIgc)" class="il-_c1b6x"/><g filter="url(#icYOh8d)"><path stroke="url(#iIv9Nic)" class="cpijggb8i"/></g><g filter="url(#i5C2LbF)"><path stroke="url(#iJ3Fx5d)" class="l97z_yb5u"/></g><g filter="url(#iWaocCe)"><path stroke="url(#iqbc5Ud)" class="mo1ay2b9h"/></g><g filter="url(#iPPLtte)"><path stroke="url(#iWTYIZd)" class="p4vclu1of"/></g><g filter="url(#iHEnBuc)"><path stroke="url(#iWBAoZb)" class="edb-5lfcd"/></g><defs><linearGradient id="iwiYw2d" x1="15.234" x2="15.203" y1="27.819" y2="26.875" gradientUnits="userSpaceOnUse"><stop offset=".291" class="a1o3ds96s"/><stop offset="1" class="wf2vl4bhc"/></linearGradient><linearGradient id="iCskouc" x1="7.438" x2="7.594" y1="14.594" y2="12.25" gradientUnits="userSpaceOnUse"><stop offset=".281" class="qosq9x3ez"/><stop offset="1" class="ceq3mjb8c"/></linearGradient><linearGradient id="iisrD8c" x1="10.664" x2="10.688" y1="14.773" y2="13.922" gradientUnits="userSpaceOnUse"><stop class="i7vq59i6u"/><stop offset="1" class="wpp8hjbeu"/></linearGradient><linearGradient id="itNxYfd" x1="3.925" x2="6.962" y1="12.179" y2="12.179" gradientUnits="userSpaceOnUse"><stop class="ijjygpy9k"/><stop offset="1" class="f7ypgacmn"/></linearGradient><linearGradient id="iz6bate" x1="16.669" x2="13.311" y1="14.085" y2="13.995" gradientUnits="userSpaceOnUse"><stop class="lbovwv01e"/><stop offset="1" class="xsrgh_bde"/></linearGradient><linearGradient id="i5aWGvc" x1="5.524" x2="5.674" y1="18.975" y2="16.612" gradientUnits="userSpaceOnUse"><stop offset=".281" class="qosq9x3ez"/><stop offset="1" class="ceq3mjb8c"/></linearGradient><linearGradient id="iFoqw1Y" x1="8.914" x2="8.912" y1="19.398" y2="18.445" gradientUnits="userSpaceOnUse"><stop class="i7vq59i6u"/><stop offset="1" class="wpp8hjbeu"/></linearGradient><linearGradient id="iPaPEGb" x1="2.391" x2="4.906" y1="16.656" y2="16.542" gradientUnits="userSpaceOnUse"><stop class="paajhccoq"/><stop offset="1" class="nvgsr2b5p"/></linearGradient><linearGradient id="ibMQ2fc" x1="16.32" x2="14.938" y1="18.371" y2="18.368" gradientUnits="userSpaceOnUse"><stop class="yfu9ofbqo"/><stop offset="1" class="xsrgh_bde"/></linearGradient><linearGradient id="izoudmd" x1="7.41" x2="7.446" y1="23.387" y2="20.844" gradientUnits="userSpaceOnUse"><stop class="kcl63g09u"/><stop offset="1" class="ceq3mjb8c"/></linearGradient><linearGradient id="iDPo8Xc" x1="10.05" x2="10.048" y1="23.784" y2="22.917" gradientUnits="userSpaceOnUse"><stop class="i7vq59i6u"/><stop offset="1" class="wpp8hjbeu"/></linearGradient><linearGradient id="iaje8eb" x1="4.534" x2="6.662" y1="21.292" y2="21.202" gradientUnits="userSpaceOnUse"><stop class="paajhccoq"/><stop offset="1" class="nvgsr2b5p"/></linearGradient><linearGradient id="icdXzsx" x1="16.313" x2="15.144" y1="22.85" y2="22.848" gradientUnits="userSpaceOnUse"><stop class="rj6s4bbff"/><stop offset="1" class="dm7u83bgz"/></linearGradient><linearGradient id="irMEq9f" x1="10.394" x2="10.573" y1="22.96" y2="24.738" gradientUnits="userSpaceOnUse"><stop offset=".169" class="i8o-uidvt"/><stop offset=".828" class="fy68_91vn"/></linearGradient><linearGradient id="ilRFbhC" x1="7.108" x2="8.784" y1="26.121" y2="26.069" gradientUnits="userSpaceOnUse"><stop class="h2u2ok43k"/><stop offset="1" class="saotcflvw"/></linearGradient><linearGradient id="iIv9Nic" x1="14.619" x2="13.939" y1="5.382" y2="10.619" gradientUnits="userSpaceOnUse"><stop class="crpmgp8oi"/><stop offset="1" class="xnma9yb1h"/></linearGradient><linearGradient id="iJ3Fx5d" x1="5.777" x2="5.773" y1="11.752" y2="12.188" gradientUnits="userSpaceOnUse"><stop class="i_3xz0k0c"/><stop offset="1" class="u-6541p_p"/></linearGradient><linearGradient id="iqbc5Ud" x1="4.257" x2="4.253" y1="16.34" y2="16.776" gradientUnits="userSpaceOnUse"><stop class="i_3xz0k0c"/><stop offset="1" class="u-6541p_p"/></linearGradient><linearGradient id="iWTYIZd" x1="6.789" x2="6.784" y1="20.902" y2="21.339" gradientUnits="userSpaceOnUse"><stop class="i_3xz0k0c"/><stop offset="1" class="u-6541p_p"/></linearGradient><linearGradient id="iWBAoZb" x1="9.389" x2="9.384" y1="25.602" y2="26.038" gradientUnits="userSpaceOnUse"><stop class="i_3xz0k0c"/><stop offset="1" class="u-6541p_p"/></linearGradient><filter id="isU4kqb" width="28.465" height="24.289" x="1.817" y="3.78" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.592157 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6812"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.627451 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_6812" result="effect2_innerShadow_20020_6812"/></filter><filter id="iiDYNId" width="3.163" height="3.347" x="14.648" y="13.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6812" stdDeviation=".15"/></filter><filter id="iwVZ1Md" width="3.631" height="3.483" x="14.129" y="17.167" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6812" stdDeviation=".15"/></filter><filter id="i78EpLv" width="3.353" height="3.679" x="14.836" y="21.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6812" stdDeviation=".15"/></filter><filter id="iRaLund" width="6.246" height="16.916" x="14.72" y="10.233" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6812" stdDeviation=".75"/></filter><filter id="icYOh8d" width="12.792" height="9.153" x="13.198" y="4.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6812" stdDeviation=".625"/></filter><filter id="i5C2LbF" width="14.446" height="4.713" x="4.013" y="9.694" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6812" stdDeviation=".75"/></filter><filter id="iWaocCe" width="16.246" height="4.69" x="1.813" y="13.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6812" stdDeviation=".75"/></filter><filter id="iPPLtte" width="13.313" height="4.25" x="4.344" y="18.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6812" stdDeviation=".75"/></filter><filter id="iHEnBuc" width="10.701" height="4.519" x="6.944" y="22.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6812" stdDeviation=".75"/></filter><radialGradient id="iDxwosV" cx="0" cy="0" r="1" gradientTransform="matrix(-23.03994 5.75988 -5.9694 -23.87805 25.836 13.9)" gradientUnits="userSpaceOnUse"><stop class="fxry_sv_t"/><stop offset=".624" class="eqzhirb3w"/></radialGradient><radialGradient id="iikJcHc" cx="0" cy="0" r="1" gradientTransform="matrix(20.14532 -8.71599 12.72828 29.41896 8.576 22.198)" gradientUnits="userSpaceOnUse"><stop offset=".678" class="dtvflvbut"/><stop offset=".966" class="uujenxbln"/></radialGradient><radialGradient id="iacj7Or" cx="0" cy="0" r="1" gradientTransform="matrix(5.76564 14.34379 -24.55123 9.86863 17.188 13.125)" gradientUnits="userSpaceOnUse"><stop offset=".903" class="wf2vl4bhc"/><stop offset=".975" class="a1o3ds96s"/></radialGradient><radialGradient id="iuEbdJc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4896 2.17151 -5.1467 -3.53049 15.8 5.056)" gradientUnits="userSpaceOnUse"><stop class="rwjsi8u9b"/><stop offset="1" class="jxtp3vx1u"/></radialGradient><radialGradient id="i6kerhd" cx="0" cy="0" r="1" gradientTransform="rotate(-2.8 309.887 -314.342)scale(1.7849 1.63088)" gradientUnits="userSpaceOnUse"><stop class="jktqmouri"/><stop offset="1" class="q607cwb8s"/></radialGradient><radialGradient id="i9Yr13w" cx="0" cy="0" r="1" gradientTransform="matrix(2.10888 -.09153 .07424 1.71053 15.351 18.909)" gradientUnits="userSpaceOnUse"><stop class="jktqmouri"/><stop offset="1" class="q607cwb8s"/></radialGradient><radialGradient id="i1hJWGw" cx="0" cy="0" r="1" gradientTransform="matrix(1.915 -.09773 .09315 1.82517 15.973 23.364)" gradientUnits="userSpaceOnUse"><stop class="jktqmouri"/><stop offset="1" class="q607cwb8s"/></radialGradient><radialGradient id="iL4aIgc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.957 -4.95244 1.21054 -1.45608 14.66 10.789)" gradientUnits="userSpaceOnUse"><stop class="c4j28d_jb"/><stop offset=".251" class="ojrun9bei"/><stop offset="1" class="eogsr-yml"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:leftwards-hand" /></template>
<style>
.a1o3ds96s {
  stop-color: var(--svg-color--f883ac, #F883AC);
}

.aspe13b4o {
  d: path("M4.29 14.454a2.406 2.406 0 0 0-.135 4.81l.945.026a2.406 2.406 0 0 0 1.4 4.393l1.37-.025a2.406 2.406 0 0 0 1.736 4.16l8.822-.336c1.33-.005 3.695-.149 5.76-1.004c3.267-1.207 5.595-4.34 5.595-8.016c0-3.715-2.38-6.876-5.702-8.054c-2.108-.888-4.283-2.362-5.205-2.986l-.06-.042l-2.82-2.098a2.536 2.536 0 0 0-3.054 4.05l1.424 1.088l-7.953-.344a2.385 2.385 0 0 0-1.378 4.4z");
}

.c4j28d_jb {
  stop-color: var(--svg-color--b86211, #B86211);
}

.ceq3mjb8c {
  stop-color: var(--svg-color--fba843, #FBA843);
  stop-opacity: 0;
}

.cpijggb8i {
  stroke-linecap: round;
  d: path("M14.948 6.205c1.48 1.398 5.871 4.074 9.292 5.653");
}

.crpmgp8oi {
  stop-color: var(--svg-color--ffeb67, #FFEB67);
}

.deak9vbee {
  d: path("M17.51 16.138c-.835-.896-2.062-1.226-2.562-1.216c1.3-.15 2.25-1.083 2.563-1.53z");
}

.dm7u83bgz {
  stop-color: var(--svg-color--f6b335, #F6B335);
  stop-opacity: 0;
}

.dtvflvbut {
  stop-color: var(--svg-color--ffd051, #FFD051);
  stop-opacity: 0;
}

.edb-5lfcd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m9.069 25.293l6.45-.268");
}

.eogsr-yml {
  stop-color: var(--svg-color--e08e11, #E08E11);
  stop-opacity: 0;
}

.eqzhirb3w {
  stop-color: var(--svg-color--f4ac2e, #F4AC2E);
}

.f7ypgacmn {
  stop-color: var(--svg-color--e69742, #E69742);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fxry_sv_t {
  stop-color: var(--svg-color--ffd556, #FFD556);
}

.fy68_91vn {
  stop-color: var(--svg-color--ea940c, #EA940C);
  stop-opacity: 0;
}

.h2u2ok43k {
  stop-color: var(--svg-color--d18b4c, #D18B4C);
}

.i_3xz0k0c {
  stop-color: var(--svg-color--ffc42e, #FFC42E);
}

.i7vq59i6u {
  stop-color: var(--svg-color--c46801, #C46801);
}

.i8o-uidvt {
  stop-color: var(--svg-color--d17502, #D17502);
}

.ijjygpy9k {
  stop-color: var(--svg-color--e69742, #E69742);
}

.il-_c1b6x {
  d: path("M17.684 10.546L12.69 5.52q-.13.13-.243.281a2.536 2.536 0 0 0 .495 3.53l1.424 1.088z");
}

.jktqmouri {
  stop-color: var(--svg-color--e78e31, #E78E31);
}

.jxtp3vx1u {
  stop-color: var(--svg-color--ffd836, #FFD836);
  stop-opacity: 0;
}

.kcl63g09u {
  stop-color: var(--svg-color--f99756, #F99756);
}

.l97z_yb5u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m6.138 11.819l10.196.463");
}

.lbovwv01e {
  stop-color: var(--svg-color--f9bc3e, #F9BC3E);
}

.ldx0mbbzq {
  d: path("m6.181 10.077l10.136.424v4.403l-11.288-.432a2.384 2.384 0 0 1 1.152-4.395");
}

.mo1ay2b9h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m3.938 16.031l11.996.44");
}

.msizombgs {
  d: path("M1.818 16.791a2.406 2.406 0 0 1 2.473-2.337c4.002.113 8.02.291 12.03.437v4.397H5.096l-.942-.024a2.406 2.406 0 0 1-2.337-2.473");
}

.nvgsr2b5p {
  stop-color: var(--svg-color--e5943d, #E5943D);
  stop-opacity: 0;
}

.o6ivf5b4i {
  stroke: var(--svg-color--fdb042, #FDB042);
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.369 12.106c-1.146 2-2.663 7.437.437 13.187");
}

.ojrun9bei {
  stop-color: var(--svg-color--e08e11, #E08E11);
}

.p4vclu1of {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M6.469 20.594h9.062");
}

.paajhccoq {
  stop-color: var(--svg-color--e5943d, #E5943D);
}

.q607cwb8s {
  stop-color: var(--svg-color--f1a624, #F1A624);
  stop-opacity: 0;
}

.qosq9x3ez {
  stop-color: var(--svg-color--fba843, #FBA843);
}

.rj6s4bbff {
  stop-color: var(--svg-color--f6b335, #F6B335);
}

.rwjsi8u9b {
  stop-color: var(--svg-color--ffdc3b, #FFDC3B);
}

.s6bul9b5u {
  d: path("M17.888 24.904c-1.038-1.052-2.16-1.435-2.752-1.422c1.538-.178 2.383-1.127 2.752-1.657z");
}

.saotcflvw {
  stop-color: var(--svg-color--d18b4c, #D18B4C);
  stop-opacity: 0;
}

.u-6541p_p {
  stop-color: var(--svg-color--ffc42e, #FFC42E);
  stop-opacity: 0;
}

.u978vfesz {
  d: path("M5.1 19.29a2.406 2.406 0 0 0 1.4 4.393l9.813-.214V19.29z");
}

.uujenxbln {
  stop-color: var(--svg-color--ffef63, #FFEF63);
}

.wf2vl4bhc {
  stop-color: var(--svg-color--ffa260, #FFA260);
  stop-opacity: 0;
}

.wpp8hjbeu {
  stop-color: var(--svg-color--fca943, #FCA943);
  stop-opacity: 0;
}

.wq5e5tu3b {
  d: path("M7.87 23.657a2.406 2.406 0 0 0 1.736 4.16l6.91-.27c0-1.342-.391-3.156-.391-4.078z");
}

.xnma9yb1h {
  stop-color: var(--svg-color--ffeb67, #FFEB67);
  stop-opacity: 0;
}

.xsrgh_bde {
  stop-color: var(--svg-color--f9bc3e, #F9BC3E);
  stop-opacity: 0;
}

.yei81-omf {
  d: path("M17.46 20.35c-1.005-.887-2.44-1.084-3.03-1.072c1.537-.177 2.66-1.281 3.03-1.81z");
}

.yfu9ofbqo {
  stop-color: var(--svg-color--f8b83a, #F8B83A);
}

</style>
