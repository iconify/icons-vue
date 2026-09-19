<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iq2ES3b)"><path fill="url(#ig6TSoa)" class="xwp779qon"/><path fill="url(#icTEbQd)" class="xwp779qon"/></g><path fill="url(#ig9o1Oe)" class="xwp779qon"/><path fill="url(#iLah8YS)" class="xwp779qon"/><path fill="url(#ib3Yrbe)" class="d9c2_gbse"/><path fill="url(#iLZ7gFb)" class="d9c2_gbse"/><path fill="url(#iMbO08b)" class="d9c2_gbse"/><path fill="url(#iMeW44d)" class="d9c2_gbse"/><path fill="url(#ihFIfgb)" class="otmc6dbqt"/><path fill="url(#iNzdiGd)" class="otmc6dbqt"/><path fill="url(#i8UJZje)" class="otmc6dbqt"/><path fill="url(#iRW24Be)" class="otmc6dbqt"/><path fill="url(#iKciQvb)" class="y_63ypjkf"/><path fill="url(#iXsusSc)" class="y_63ypjkf"/><path fill="url(#imvJPae)" class="y_63ypjkf"/><path fill="url(#iDE2Xde)" class="y_63ypjkf"/><path fill="url(#ibEgxce)" class="usmfspbqh"/><path fill="url(#ilqMrEt)" class="usmfspbqh"/><g filter="url(#iuVPPBc)"><path fill="url(#ijJfGMH)" class="e0a3rcc-m"/></g><g filter="url(#ibbcgpc)"><path fill="url(#i2fsQ4c)" class="ld8nr9a8m"/></g><g filter="url(#iAjahzc)"><path fill="url(#iURku2B)" class="wwra3x1fo"/></g><g filter="url(#iAnwGHd)"><path class="pjbbw6y2v"/></g><path fill="url(#iusg8Bb)" class="htn9t_b-d"/><g filter="url(#icLstee)"><path stroke="url(#ioKNLZT)" class="ke7j04pfg"/></g><g filter="url(#ikDbVod)"><path stroke="url(#i8SCKuc)" class="ad_vo5bce"/></g><g filter="url(#idyqPkd)"><path stroke="url(#i9mxFAI)" class="g7-px85lq"/></g><g filter="url(#iFsBmBs)"><path stroke="url(#i4QhlLd)" class="y3s8c85ag"/></g><g filter="url(#i13VEwd)"><path stroke="url(#ikvc6Be)" class="zwd2w-blg"/></g><defs><linearGradient id="ig9o1Oe" x1="15.234" x2="15.203" y1="26.939" y2="25.995" gradientUnits="userSpaceOnUse"><stop offset=".291" class="rj8n4wbdl"/><stop offset="1" class="v2ysnbbyc"/></linearGradient><linearGradient id="ib3Yrbe" x1="7.438" x2="7.594" y1="13.714" y2="11.37" gradientUnits="userSpaceOnUse"><stop offset=".281" class="ynumcwbdy"/><stop offset="1" class="h-z60ta5s"/></linearGradient><linearGradient id="iLZ7gFb" x1="10.664" x2="10.672" y1="13.893" y2="13.398" gradientUnits="userSpaceOnUse"><stop class="l86o1hxxn"/><stop offset="1" class="fvoye7boa"/></linearGradient><linearGradient id="iMbO08b" x1="3.925" x2="6.962" y1="11.299" y2="11.299" gradientUnits="userSpaceOnUse"><stop class="c_kjg6q6l"/><stop offset="1" class="dv8x83bgq"/></linearGradient><linearGradient id="iMeW44d" x1="15.836" x2="13.311" y1="13.24" y2="13.114" gradientUnits="userSpaceOnUse"><stop class="aav_ec71z"/><stop offset="1" class="escdleb1c"/></linearGradient><linearGradient id="ihFIfgb" x1="5.655" x2="5.672" y1="18.408" y2="15.733" gradientUnits="userSpaceOnUse"><stop offset=".159" class="sa4_3-bcu"/><stop offset="1" class="eqankbbsy"/></linearGradient><linearGradient id="iNzdiGd" x1="8.906" x2="8.919" y1="18.578" y2="17.547" gradientUnits="userSpaceOnUse"><stop class="dk44srbkn"/><stop offset="1" class="h65c54lsi"/></linearGradient><linearGradient id="i8UJZje" x1="1.817" x2="3.969" y1="15.563" y2="15.719" gradientUnits="userSpaceOnUse"><stop class="uu5o3cekc"/><stop offset="1" class="hmitd-bry"/></linearGradient><linearGradient id="iRW24Be" x1="16.32" x2="14.583" y1="17.491" y2="17.378" gradientUnits="userSpaceOnUse"><stop class="y0z695rxf"/><stop offset="1" class="e10ayxp8t"/></linearGradient><linearGradient id="iKciQvb" x1="7.586" x2="7.508" y1="22.803" y2="20.607" gradientUnits="userSpaceOnUse"><stop class="td4cxm13o"/><stop offset="1" class="k8irvwbnq"/></linearGradient><linearGradient id="iXsusSc" x1="10.05" x2="10.048" y1="22.904" y2="22.037" gradientUnits="userSpaceOnUse"><stop class="amjlqyads"/><stop offset="1" class="mjoo1lluw"/></linearGradient><linearGradient id="imvJPae" x1="4.534" x2="6.662" y1="20.412" y2="20.322" gradientUnits="userSpaceOnUse"><stop class="l8t0ssbol"/><stop offset="1" class="y15vj8b6r"/></linearGradient><linearGradient id="iDE2Xde" x1="16.313" x2="15.144" y1="21.97" y2="21.968" gradientUnits="userSpaceOnUse"><stop class="wddcmor5x"/><stop offset="1" class="y7wlmij2n"/></linearGradient><linearGradient id="ibEgxce" x1="10.394" x2="10.573" y1="22.08" y2="23.858" gradientUnits="userSpaceOnUse"><stop offset=".169" class="u24mgdcov"/><stop offset=".828" class="ycdf2bbtp"/></linearGradient><linearGradient id="ilqMrEt" x1="7.108" x2="8.784" y1="25.241" y2="25.189" gradientUnits="userSpaceOnUse"><stop class="kkmfbvbin"/><stop offset="1" class="x9ass5qdk"/></linearGradient><linearGradient id="ioKNLZT" x1="14.619" x2="13.939" y1="4.502" y2="9.739" gradientUnits="userSpaceOnUse"><stop class="qsx826m4r"/><stop offset="1" class="cz-uxbckr"/></linearGradient><linearGradient id="i8SCKuc" x1="5.777" x2="5.773" y1="10.872" y2="11.308" gradientUnits="userSpaceOnUse"><stop class="vv_wqmpsf"/><stop offset="1" class="xc20l4s3d"/></linearGradient><linearGradient id="i9mxFAI" x1="3.513" x2="3.51" y1="15.087" y2="15.502" gradientUnits="userSpaceOnUse"><stop class="vv_wqmpsf"/><stop offset="1" class="xc20l4s3d"/></linearGradient><linearGradient id="i4QhlLd" x1="6.148" x2="6.126" y1="19.568" y2="20.51" gradientUnits="userSpaceOnUse"><stop class="vv_wqmpsf"/><stop offset="1" class="xc20l4s3d"/></linearGradient><linearGradient id="ikvc6Be" x1="8.84" x2="8.838" y1="24.106" y2="24.359" gradientUnits="userSpaceOnUse"><stop class="vv_wqmpsf"/><stop offset="1" class="xc20l4s3d"/></linearGradient><filter id="iq2ES3b" width="28.465" height="24.039" x="1.817" y="2.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.129412 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6877"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.113725 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_6877" result="effect2_innerShadow_20020_6877"/></filter><filter id="iuVPPBc" width="3.163" height="3.347" x="14.648" y="12.211" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6877" stdDeviation=".15"/></filter><filter id="ibbcgpc" width="3.631" height="3.483" x="14.129" y="16.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6877" stdDeviation=".15"/></filter><filter id="iAjahzc" width="3.353" height="3.679" x="14.836" y="20.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6877" stdDeviation=".15"/></filter><filter id="iAnwGHd" width="6.246" height="16.916" x="13.694" y="9.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6877" stdDeviation=".75"/></filter><filter id="icLstee" width="12.792" height="9.153" x="13.198" y="3.575" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6877" stdDeviation=".625"/></filter><filter id="ikDbVod" width="14.446" height="4.713" x="4.013" y="8.814" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6877" stdDeviation=".75"/></filter><filter id="idyqPkd" width="16.246" height="4.69" x="1.813" y="13.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6877" stdDeviation=".75"/></filter><filter id="iFsBmBs" width="13.313" height="4.25" x="4.344" y="17.589" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6877" stdDeviation=".75"/></filter><filter id="i13VEwd" width="10.701" height="4.519" x="6.944" y="22.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6877" stdDeviation=".75"/></filter><radialGradient id="ig6TSoa" cx="0" cy="0" r="1" gradientTransform="rotate(170.048 14.132 8.332)scale(27.1022 28.0881)" gradientUnits="userSpaceOnUse"><stop class="xm34y9b_d"/><stop offset=".624" class="l2hgn7b9e"/></radialGradient><radialGradient id="icTEbQd" cx="0" cy="0" r="1" gradientTransform="matrix(22.4244 -5.89812 8.61325 32.7472 8.576 21.318)" gradientUnits="userSpaceOnUse"><stop offset=".828" class="f6yh_7snt"/><stop offset="1" class="a5c9r5b5q"/></radialGradient><radialGradient id="iLah8YS" cx="0" cy="0" r="1" gradientTransform="rotate(67.003 -.656 19.105)scale(15.0532 25.7656)" gradientUnits="userSpaceOnUse"><stop offset=".963" class="o_93gvb8s"/><stop offset="1" class="nrth8gbsy"/></radialGradient><radialGradient id="ijJfGMH" cx="0" cy="0" r="1" gradientTransform="matrix(2.5625 -.0872 .07968 2.34138 14.948 13.885)" gradientUnits="userSpaceOnUse"><stop class="lub5dyb4n"/><stop offset="1" class="z-7ts0buu"/></radialGradient><radialGradient id="i2fsQ4c" cx="0" cy="0" r="1" gradientTransform="matrix(3.03125 -.09153 .07422 2.45803 14.43 18.029)" gradientUnits="userSpaceOnUse"><stop class="lub5dyb4n"/><stop offset="1" class="z-7ts0buu"/></radialGradient><radialGradient id="iURku2B" cx="0" cy="0" r="1" gradientTransform="matrix(2.75258 -.09773 .09316 2.62374 15.136 22.484)" gradientUnits="userSpaceOnUse"><stop class="lub5dyb4n"/><stop offset="1" class="z-7ts0buu"/></radialGradient><radialGradient id="iusg8Bb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.957 -4.95244 1.21054 -1.45608 14.66 9.909)" gradientUnits="userSpaceOnUse"><stop class="wx---x8an"/><stop offset=".251" class="lk_c_mter"/><stop offset="1" class="dwethdcek"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:leftwards-hand-dark" /></template>
<style>
.a5c9r5b5q {
  stop-color: var(--svg-color--64504e, #64504E);
}

.aav_ec71z {
  stop-color: var(--svg-color--50383a, #50383A);
}

.ad_vo5bce {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m6.138 10.939l10.196.463");
}

.amjlqyads {
  stop-color: var(--svg-color--271318, #271318);
}

.c_kjg6q6l {
  stop-color: var(--svg-color--402c2a, #402C2A);
}

.cz-uxbckr {
  stop-color: var(--svg-color--5a423e, #5A423E);
  stop-opacity: 0;
}

.d9c2_gbse {
  d: path("m6.181 9.197l10.136.424v4.403l-11.288-.432A2.384 2.384 0 0 1 6.18 9.197");
}

.dk44srbkn {
  stop-color: var(--svg-color--170708, #170708);
}

.dv8x83bgq {
  stop-color: var(--svg-color--402c2a, #402C2A);
  stop-opacity: 0;
}

.dwethdcek {
  stop-color: var(--svg-color--321d1e, #321D1E);
  stop-opacity: 0;
}

.e0a3rcc-m {
  d: path("M17.51 15.258c-.835-.896-2.062-1.226-2.562-1.216c1.3-.15 2.25-1.083 2.563-1.531z");
}

.e10ayxp8t {
  stop-color: var(--svg-color--4f3738, #4F3738);
  stop-opacity: 0;
}

.eqankbbsy {
  stop-color: var(--svg-color--3d222c, #3D222C);
  stop-opacity: 0;
}

.escdleb1c {
  stop-color: var(--svg-color--50383a, #50383A);
  stop-opacity: 0;
}

.f6yh_7snt {
  stop-color: var(--svg-color--5e4947, #5E4947);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvoye7boa {
  stop-color: var(--svg-color--251211, #251211);
  stop-opacity: 0;
}

.g7-px85lq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m3.938 15.151l11.996.44");
}

.h-z60ta5s {
  stop-color: var(--svg-color--3b2229, #3B2229);
  stop-opacity: 0;
}

.h65c54lsi {
  stop-color: var(--svg-color--3f222e, #3F222E);
  stop-opacity: 0;
}

.hmitd-bry {
  stop-color: var(--svg-color--3e2a29, #3E2A29);
  stop-opacity: 0;
}

.htn9t_b-d {
  d: path("M17.684 9.666L12.69 4.64q-.13.13-.243.281a2.536 2.536 0 0 0 .495 3.53l1.424 1.088z");
}

.k8irvwbnq {
  stop-color: var(--svg-color--3c212d, #3C212D);
  stop-opacity: 0;
}

.ke7j04pfg {
  stroke-linecap: round;
  d: path("M14.948 5.325c1.48 1.398 5.871 4.074 9.292 5.653");
}

.kkmfbvbin {
  stop-color: var(--svg-color--503e3b, #503E3B);
}

.l2hgn7b9e {
  stop-color: var(--svg-color--482f32, #482F32);
}

.l86o1hxxn {
  stop-color: var(--svg-color--251211, #251211);
}

.l8t0ssbol {
  stop-color: var(--svg-color--513f3b, #513F3B);
}

.ld8nr9a8m {
  d: path("M17.46 19.47c-1.005-.887-2.44-1.084-3.03-1.072c1.537-.177 2.66-1.281 3.03-1.81z");
}

.lk_c_mter {
  stop-color: var(--svg-color--321d1e, #321D1E);
}

.lub5dyb4n {
  stop-color: var(--svg-color--392523, #392523);
}

.mjoo1lluw {
  stop-color: var(--svg-color--3a202f, #3A202F);
  stop-opacity: 0;
}

.nrth8gbsy {
  stop-color: var(--svg-color--503c50, #503C50);
}

.o_93gvb8s {
  stop-color: var(--svg-color--412535, #412535);
  stop-opacity: 0;
}

.otmc6dbqt {
  d: path("M1.818 15.911a2.406 2.406 0 0 1 2.473-2.337c4.002.113 8.02.291 12.03.437v4.397H5.096l-.942-.024a2.406 2.406 0 0 1-2.337-2.473");
}

.pjbbw6y2v {
  stroke: var(--svg-color--482f30, #482F30);
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.343 11.226c-1.146 2-2.663 7.437.437 13.187");
}

.qsx826m4r {
  stop-color: var(--svg-color--5a423e, #5A423E);
}

.rj8n4wbdl {
  stop-color: var(--svg-color--4e3750, #4E3750);
}

.sa4_3-bcu {
  stop-color: var(--svg-color--3d222c, #3D222C);
}

.td4cxm13o {
  stop-color: var(--svg-color--3c212d, #3C212D);
}

.u24mgdcov {
  stop-color: var(--svg-color--261413, #261413);
}

.usmfspbqh {
  d: path("M7.87 22.777a2.406 2.406 0 0 0 1.736 4.16l6.91-.27c0-1.342-.391-3.156-.391-4.078z");
}

.uu5o3cekc {
  stop-color: var(--svg-color--3e2a29, #3E2A29);
}

.v2ysnbbyc {
  stop-color: var(--svg-color--3d2133, #3D2133);
  stop-opacity: 0;
}

.vv_wqmpsf {
  stop-color: var(--svg-color--4b3332, #4B3332);
}

.wddcmor5x {
  stop-color: var(--svg-color--4c3436, #4C3436);
}

.wwra3x1fo {
  d: path("M17.888 24.024c-1.038-1.052-2.16-1.435-2.752-1.422c1.538-.178 2.383-1.127 2.752-1.657z");
}

.wx---x8an {
  stop-color: var(--svg-color--1b0b0a, #1B0B0A);
}

.x9ass5qdk {
  stop-color: var(--svg-color--2a1a19, #2A1A19);
  stop-opacity: 0;
}

.xc20l4s3d {
  stop-color: var(--svg-color--4b3332, #4B3332);
  stop-opacity: 0;
}

.xm34y9b_d {
  stop-color: var(--svg-color--65514f, #65514F);
}

.xwp779qon {
  d: path("M4.29 13.574a2.406 2.406 0 0 0-.135 4.81l.945.026a2.406 2.406 0 0 0 1.4 4.393l1.37-.025a2.406 2.406 0 0 0 1.736 4.16l8.822-.336c1.33-.005 3.695-.149 5.76-1.004c3.267-1.207 5.595-4.34 5.595-8.015c0-3.716-2.38-6.877-5.702-8.055c-2.108-.888-4.283-2.362-5.205-2.986l-.06-.042l-2.82-2.098a2.536 2.536 0 0 0-3.054 4.05l1.424 1.088l-7.953-.344a2.385 2.385 0 0 0-1.378 4.4z");
}

.y_63ypjkf {
  d: path("M5.1 18.41a2.406 2.406 0 0 0 1.4 4.393l9.813-.214V18.41z");
}

.y0z695rxf {
  stop-color: var(--svg-color--4f3738, #4F3738);
}

.y15vj8b6r {
  stop-color: var(--svg-color--2b1a17, #2B1A17);
  stop-opacity: 0;
}

.y3s8c85ag {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M6.469 19.714h9.062");
}

.y7wlmij2n {
  stop-color: var(--svg-color--4c3436, #4C3436);
  stop-opacity: 0;
}

.ycdf2bbtp {
  stop-color: var(--svg-color--3d2623, #3D2623);
  stop-opacity: 0;
}

.ynumcwbdy {
  stop-color: var(--svg-color--3b2229, #3B2229);
}

.z-7ts0buu {
  stop-color: var(--svg-color--392523, #392523);
  stop-opacity: 0;
}

.zwd2w-blg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("m9.069 24.413l6.45-.268");
}

</style>
