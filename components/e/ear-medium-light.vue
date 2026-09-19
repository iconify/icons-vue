<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="jdr7kzq4e"/><g filter="url(#iVSSfEe)"><ellipse fill="url(#iMa4kje)" transform="rotate(26.087 17.338 9.08)" class="r4xp77bwq"/></g><g filter="url(#iiOO9ec)"><path fill="url(#idre9ab)" class="crbyzbt1f"/><path fill="url(#ibTFitb)" class="crbyzbt1f"/></g><g filter="url(#icyBQpb)"><circle fill="url(#icLiyTc)" class="yx_4vcb_f"/></g><circle fill="url(#iFYvTtd)" class="m7rma2bnk"/><circle fill="url(#ikAixvw)" class="m7rma2bnk"/><g filter="url(#i80yemD)"><circle class="tp1chbcdf"/></g><g filter="url(#iqdU27c)"><path fill="url(#iCRkNwm)" class="o5ihkcskr"/><path fill="url(#iHgXtmc)" class="o5ihkcskr"/></g><path fill="url(#iX0Ilgb)" class="o5ihkcskr"/><path fill="url(#imqiMxe)" class="o5ihkcskr"/><path fill="url(#i7VBncb)" class="o5ihkcskr"/><path fill="url(#iA5k7oe)" class="o5ihkcskr"/><path fill="url(#iQvZ1tA)" class="o5ihkcskr"/><g filter="url(#iJlRkGc)"><path stroke="url(#i4o5dxc)" class="qk8scsbaf"/></g><g filter="url(#iCIh7Wc)"><path stroke="url(#i80hjwd)" class="ivry3481r"/></g><defs><radialGradient id="iMa4kje" cx="0" cy="0" r="1" gradientTransform="rotate(-91.906 15.31 -1.52)scale(8.88629 15.4978)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="trcx2qb5r"/><stop offset=".922" class="v05g5nbno"/></radialGradient><radialGradient id="ikAixvw" cx="0" cy="0" r="1" gradientTransform="matrix(-2.10816 1.52067 -1.73662 -2.40753 14.464 20.918)" gradientUnits="userSpaceOnUse"><stop class="pk2_uvofd"/><stop offset="1" class="pkzs1bb5w"/></radialGradient><radialGradient id="iHgXtmc" cx="0" cy="0" r="1" gradientTransform="matrix(3.875 -5.5625 6.22805 4.33864 17.5 10.83)" gradientUnits="userSpaceOnUse"><stop offset=".585" class="emwabp4fw"/><stop offset="1" class="grzcxhmih"/></radialGradient><radialGradient id="iX0Ilgb" cx="0" cy="0" r="1" gradientTransform="matrix(.14338 -4.62474 6.13434 .19019 23.232 15.266)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="d3ikkpb5y"/><stop offset="1" class="sr9kiobma"/></radialGradient><radialGradient id="imqiMxe" cx="0" cy="0" r="1" gradientTransform="rotate(115.159 1.796 17.183)scale(4.97005 4.84669)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="w4pkpsbkf"/><stop offset="1" class="tuo24kjcb"/></radialGradient><radialGradient id="i7VBncb" cx="0" cy="0" r="1" gradientTransform="rotate(-115.896 19.594 6.144)scale(26.3315 19.1931)" gradientUnits="userSpaceOnUse"><stop offset=".953" class="ov2d-rbnh"/><stop offset="1" class="g8y54dbuj"/></radialGradient><radialGradient id="iA5k7oe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.14 21.87883 -17.0804 -2.45134 14.584 7.982)" gradientUnits="userSpaceOnUse"><stop offset=".837" class="b7xtxdwgx"/><stop offset="1" class="mxh-2vbgw"/></radialGradient><radialGradient id="iQvZ1tA" cx="0" cy="0" r="1" gradientTransform="matrix(2.09375 0 0 3.71875 10.344 22.142)" gradientUnits="userSpaceOnUse"><stop class="kr77r6b7q"/><stop offset="1" class="n1nhqibha"/><stop offset="1" class="y69jgzb9u"/></radialGradient><linearGradient id="idre9ab" x1="12.875" x2="10.121" y1="12.579" y2="18.173" gradientUnits="userSpaceOnUse"><stop class="bne7dsbcl"/><stop offset="1" class="lwg_i8b5w"/></linearGradient><linearGradient id="ibTFitb" x1="13.563" x2="15.563" y1="27.517" y2="21.923" gradientUnits="userSpaceOnUse"><stop offset=".218" class="jl8dr8f0s"/><stop offset="1" class="ckm_w_bgk"/></linearGradient><linearGradient id="icLiyTc" x1="14.509" x2="12.212" y1="20.489" y2="24.533" gradientUnits="userSpaceOnUse"><stop offset=".34" class="dkjt8_o6m"/><stop offset="1" class="ojom8obgb"/></linearGradient><linearGradient id="iFYvTtd" x1="11.755" x2="11.755" y1="19.142" y2="25.142" gradientUnits="userSpaceOnUse"><stop class="trqvfobih"/><stop offset="1" class="khw5u_pgi"/></linearGradient><linearGradient id="iCRkNwm" x1="11.563" x2="20" y1="31.517" y2="-.858" gradientUnits="userSpaceOnUse"><stop class="m8zz4squb"/><stop offset="1" class="nnkw3ubao"/></linearGradient><linearGradient id="i4o5dxc" x1="24.971" x2="17.565" y1="11.235" y2="3.423" gradientUnits="userSpaceOnUse"><stop class="u2e_6xu1e"/><stop offset=".51" class="i9tykjb7d"/><stop offset="1" class="u2e_6xu1e"/></linearGradient><linearGradient id="i80hjwd" x1="8.441" x2="21.379" y1="2.017" y2="24.121" gradientUnits="userSpaceOnUse"><stop class="u2e_6xu1e"/><stop offset=".698" class="i9tykjb7d"/></linearGradient><filter id="iVSSfEe" width="15.705" height="12.527" x="9.486" y="2.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4660" stdDeviation=".5"/></filter><filter id="iiOO9ec" width="12.531" height="17.719" x="7.531" y="11.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4660" stdDeviation=".25"/></filter><filter id="icyBQpb" width="7.872" height="7.872" x="8.005" y="18.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4660" stdDeviation=".375"/></filter><filter id="i80yemD" width="6.128" height="6.128" x="8.691" y="19.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4660" stdDeviation=".25"/></filter><filter id="iqdU27c" width="19.085" height="27.786" x="6.708" y="2.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.580392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4660"/></filter><filter id="iJlRkGc" width="12.094" height="12.656" x="14.44" y="1.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4660" stdDeviation=".75"/></filter><filter id="iCIh7Wc" width="13.063" height="23.361" x="6.941" y="6.937" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4660" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ear-medium-light" /></template>
<style>
.b7xtxdwgx {
  stop-color: var(--svg-color--bb738e, #BB738E);
  stop-opacity: 0;
}

.bne7dsbcl {
  stop-color: var(--svg-color--b8694e, #B8694E);
}

.ckm_w_bgk {
  stop-color: var(--svg-color--bf8569, #BF8569);
  stop-opacity: 0;
}

.crbyzbt1f {
  d: path("M12.577 28.735c-3.288-.25-4.546-2.063-4.546-5.304V12.173l2.344-.156l9.188 9.156l-2.938 4.969c-.989 1.845-1.68 2.593-4.049 2.593");
}

.d3ikkpb5y {
  stop-color: var(--svg-color--e9af97, #E9AF97);
}

.dkjt8_o6m {
  stop-color: var(--svg-color--fbc19c, #FBC19C);
}

.emwabp4fw {
  stop-color: var(--svg-color--c17c71, #C17C71);
}

.ft5dv1b6b {
  fill: none;
}

.g8y54dbuj {
  stop-color: var(--svg-color--c29a7c, #C29A7C);
}

.grzcxhmih {
  stop-color: var(--svg-color--c17c71, #C17C71);
  stop-opacity: 0;
}

.i9tykjb7d {
  stop-color: var(--svg-color--fdccaa, #FDCCAA);
}

.ivry3481r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.19 9.187v14.705c.022.895.334 3.408 3.063 4.03c2.297.525 3.625-.687 4.276-1.905l1.224-2.125");
}

.jdr7kzq4e {
  fill: var(--svg-color--ecb299, #ECB299);
  d: path("M6.708 23.43c0 3.242 2.581 6.18 5.868 6.431c2.37 0 4.459-1.374 5.447-3.22l5.756-10.19a9.292 9.292 0 1 0-17.072-5.084z");
}

.jl8dr8f0s {
  stop-color: var(--svg-color--bf8569, #BF8569);
}

.khw5u_pgi {
  stop-color: var(--svg-color--d89485, #D89485);
}

.kr77r6b7q {
  stop-color: var(--svg-color--ebb19a, #EBB19A);
}

.lwg_i8b5w {
  stop-color: var(--svg-color--b8694e, #B8694E);
  stop-opacity: 0;
}

.m7rma2bnk {
  cx: 11.755px;
  cy: 22.142px;
  r: 3px;
}

.m8zz4squb {
  stop-color: var(--svg-color--d89d8c, #D89D8C);
}

.mxh-2vbgw {
  stop-color: var(--svg-color--bb738e, #BB738E);
}

.n1nhqibha {
  stop-color: var(--svg-color--b5877c, #B5877C);
  stop-opacity: 0;
}

.nnkw3ubao {
  stop-color: var(--svg-color--e7ba93, #E7BA93);
}

.o5ihkcskr {
  d: path("M18.167 22.696a1.8 1.8 0 0 0-2.439.69l-.859 1.52l-.018.035c-.366.682-1.156 1.316-2.135 1.316c-1.255 0-2.408-1.428-2.408-2.826V11.367a5.692 5.692 0 1 1 11.315.891c-.147.94.126 1.974.943 2.46c.9.537 2.084.21 2.37-.797a9.292 9.292 0 1 0-18.23-2.554v12.064c.002 3.24 2.583 6.18 5.87 6.43c2.37 0 4.459-1.374 5.447-3.22l.84-1.485a1.8 1.8 0 0 0-.696-2.46");
}

.ojom8obgb {
  stop-color: var(--svg-color--a86540, #A86540);
}

.ov2d-rbnh {
  stop-color: var(--svg-color--c29a7c, #C29A7C);
  stop-opacity: 0;
}

.pk2_uvofd {
  stop-color: var(--svg-color--fdc8a7, #FDC8A7);
}

.pkzs1bb5w {
  stop-color: var(--svg-color--fdc8a7, #FDC8A7);
  stop-opacity: 0;
}

.qk8scsbaf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.94 3.579c2.291.375 6.919 2.431 7.094 7.656");
}

.r4xp77bwq {
  cx: 17.338px;
  cy: 9.081px;
  rx: 7.28px;
  ry: 4.652px;
}

.sr9kiobma {
  stop-color: var(--svg-color--e9af97, #E9AF97);
  stop-opacity: 0;
}

.tp1chbcdf {
  cx: 11.755px;
  cy: 22.142px;
  r: 2.564px;
  fill: var(--svg-color--eaaf98, #EAAF98);
}

.trcx2qb5r {
  stop-color: var(--svg-color--b66e6c, #B66E6C);
  stop-opacity: 0;
}

.trqvfobih {
  stop-color: var(--svg-color--efb792, #EFB792);
}

.tuo24kjcb {
  stop-color: var(--svg-color--edb49a, #EDB49A);
  stop-opacity: 0;
}

.u2e_6xu1e {
  stop-color: var(--svg-color--fdccaa, #FDCCAA);
  stop-opacity: 0;
}

.v05g5nbno {
  stop-color: var(--svg-color--b66e6c, #B66E6C);
}

.w4pkpsbkf {
  stop-color: var(--svg-color--edb49a, #EDB49A);
}

.y69jgzb9u {
  stop-color: var(--svg-color--ebb19a, #EBB19A);
  stop-opacity: 0;
}

.yx_4vcb_f {
  cx: 11.941px;
  cy: 22.328px;
  r: 3.186px;
}

</style>
