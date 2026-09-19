<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iODR5Qd)"><path class="rna5z7w0d"/></g><path fill="url(#iDSv5Rd)" class="dfytqvbtn"/><path fill="url(#ivzAGqp)" class="dfytqvbtn"/><path fill="url(#igGOy6l)" class="dfytqvbtn"/><g filter="url(#imQ19bc)"><path class="tsclx3b3b"/></g><g filter="url(#igCh8id)"><path class="dyzapwyss"/></g><g filter="url(#iddsi6b)"><path class="dy9bgzbsh"/></g><g filter="url(#inPrKfb)"><path fill="url(#iKJ8XiX)" class="fvqz7gbma"/><path fill="url(#iC8oaAc)" class="fvqz7gbma"/></g><path fill="url(#i8v4fzd)" class="fvqz7gbma"/><path fill="url(#i0CeHcy)" class="fvqz7gbma"/><g filter="url(#iDi81Pd)"><path fill="url(#iZ7lusG)" class="n6e81rbnm"/><path fill="url(#iV7Uufe)" class="n6e81rbnm"/><path fill="url(#iCgvPAc)" class="n6e81rbnm"/><path fill="url(#iQFVPbe)" class="n6e81rbnm"/></g><g filter="url(#iL8F1Ba)"><path fill="url(#iBgDEpe)" class="m8cr0gb9p"/></g><g filter="url(#itEVeEz)"><rect transform="rotate(-3.35 7.459 13.89)" class="aqdvvfb8n"/></g><g filter="url(#iCG5WRc)"><rect fill="url(#irETMrd)" transform="rotate(-1.407 12.141 11.807)" class="ygez98-kq"/></g><g filter="url(#ib4YelC)"><rect transform="rotate(-1.407 17.402 11.489)" class="w_i9pivku"/></g><path fill="url(#iHlg9AN)" class="wxce1m7zf"/><path fill="url(#iaGDGve)" class="wxce1m7zf"/><path fill="url(#i4EZFib)" class="wxce1m7zf"/><g filter="url(#ivV7tAb)"><path stroke="url(#i2OT1eU)" class="h3qumrbim"/></g><g filter="url(#ijmMitb)"><rect class="sz1do8gnu"/></g><defs><filter id="iODR5Qd" width="20.934" height="28.788" x="4.958" y="1.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.6"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.992157 0 0 0 0 0.54902 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5564"/></filter><filter id="imQ19bc" width="14.516" height="10.203" x="11.531" y="13.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5564" stdDeviation="1.25"/></filter><filter id="igCh8id" width="9.153" height="11.219" x="4.097" y="11.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5564" stdDeviation="1.25"/></filter><filter id="iddsi6b" width="9.825" height="12.747" x="7.948" y="10.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5564" stdDeviation="1.25"/></filter><filter id="inPrKfb" width="5.431" height="8.136" x="4.958" y="12.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.662745 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5564"/></filter><filter id="iDi81Pd" width="5.272" height="8.719" x="9.805" y="10.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.631373 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5564"/></filter><filter id="iL8F1Ba" width="5.414" height="9.427" x="14.936" y="10.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.584314 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5564"/></filter><filter id="itEVeEz" width="5.091" height="7.583" x="6.014" y="12.332" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5564" stdDeviation=".75"/></filter><filter id="iCG5WRc" width="5.019" height="8.302" x="10.665" y="10.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5564" stdDeviation=".75"/></filter><filter id="ib4YelC" width="5.51" height="9.019" x="15.932" y="9.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5564" stdDeviation=".75"/></filter><filter id="ivV7tAb" width="8.894" height="7.704" x="16.387" y="15.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5564" stdDeviation=".625"/></filter><filter id="ijmMitb" width="5.688" height="15.594" x="20.469" y="1.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5564" stdDeviation="1"/></filter><linearGradient id="ivzAGqp" x1="26.094" x2="20.656" y1="12.219" y2="12.219" gradientUnits="userSpaceOnUse"><stop class="j_u2hgojt"/><stop offset="1" class="nz3671a2d"/></linearGradient><linearGradient id="iKJ8XiX" x1="7.673" x2="7.673" y1="12.438" y2="19.531" gradientUnits="userSpaceOnUse"><stop class="ni_pyug7k"/><stop offset="1" class="zir7o27xr"/></linearGradient><linearGradient id="iC8oaAc" x1="10.719" x2="8.956" y1="15.721" y2="15.837" gradientUnits="userSpaceOnUse"><stop class="iw0ta6tlw"/><stop offset="1" class="rfm1mc8uy"/></linearGradient><linearGradient id="iZ7lusG" x1="12.441" x2="12.441" y1="11.234" y2="20.313" gradientUnits="userSpaceOnUse"><stop class="m8a52jbjp"/><stop offset="1" class="znr-lcc7s"/></linearGradient><linearGradient id="iV7Uufe" x1="15.398" x2="13.686" y1="14.753" y2="14.855" gradientUnits="userSpaceOnUse"><stop class="ay4016bbi"/><stop offset="1" class="f1d5fxxtc"/></linearGradient><linearGradient id="iBgDEpe" x1="15.926" x2="19.993" y1="13.868" y2="13.868" gradientUnits="userSpaceOnUse"><stop class="tdl82ibjz"/><stop offset="1" class="t4xzuwzej"/></linearGradient><linearGradient id="iHlg9AN" x1="23.448" x2="19.816" y1="17.178" y2="21.929" gradientUnits="userSpaceOnUse"><stop class="xv0941b3r"/><stop offset="1" class="jwnwrcbqf"/></linearGradient><linearGradient id="i4EZFib" x1="21.829" x2="21.793" y1="26.284" y2="22.217" gradientUnits="userSpaceOnUse"><stop offset=".382" class="kbivl4mwv"/><stop offset="1" class="wolgahxqu"/></linearGradient><linearGradient id="i2OT1eU" x1="20.313" x2="23.821" y1="17.781" y2="20.397" gradientUnits="userSpaceOnUse"><stop offset=".452" class="j5djnfbxg"/><stop offset="1" class="glp6n8btl"/></linearGradient><radialGradient id="iDSv5Rd" cx="0" cy="0" r="1" gradientTransform="rotate(-127.155 16.667 3.155)scale(10.0376 7.02112)" gradientUnits="userSpaceOnUse"><stop class="dqdy8qbll"/><stop offset="1" class="vq0_sbcit"/></radialGradient><radialGradient id="igGOy6l" cx="0" cy="0" r="1" gradientTransform="matrix(-1 1.28124 -1.43471 -1.1198 23.438 3.875)" gradientUnits="userSpaceOnUse"><stop class="jmrhb8bgs"/><stop offset="1" class="pz6alqb9u"/></radialGradient><radialGradient id="i8v4fzd" cx="0" cy="0" r="1" gradientTransform="rotate(-74.982 16.702 5.776)scale(1.9065 4.42929)" gradientUnits="userSpaceOnUse"><stop class="wdfzl_kyi"/><stop offset="1" class="o-cktxbbz"/></radialGradient><radialGradient id="i0CeHcy" cx="0" cy="0" r="1" gradientTransform="rotate(163.749 4.24 7.425)scale(1.10333 2.13513)" gradientUnits="userSpaceOnUse"><stop class="jagc-vbbt"/><stop offset="1" class="dyr_s7bji"/></radialGradient><radialGradient id="iCgvPAc" cx="0" cy="0" r="1" gradientTransform="matrix(.18748 -2.53126 5.39234 .3994 12.032 19.75)" gradientUnits="userSpaceOnUse"><stop class="wdfzl_kyi"/><stop offset="1" class="o-cktxbbz"/></radialGradient><radialGradient id="iQFVPbe" cx="0" cy="0" r="1" gradientTransform="matrix(-.67768 .30875 -.56066 -1.2306 15.077 12.7)" gradientUnits="userSpaceOnUse"><stop class="jagc-vbbt"/><stop offset="1" class="dyr_s7bji"/></radialGradient><radialGradient id="irETMrd" cx="0" cy="0" r="1" gradientTransform="rotate(91.407 -.252 13.383)scale(7.23413 3.88646)" gradientUnits="userSpaceOnUse"><stop class="shz-33bia"/><stop offset="1" class="b0wns5brh"/></radialGradient><radialGradient id="iaGDGve" cx="0" cy="0" r="1" gradientTransform="matrix(3.40306 3.0913 -2.37051 2.60958 18.893 21.933)" gradientUnits="userSpaceOnUse"><stop class="x5_tf7bfb"/><stop offset="1" class="fq034wb8i"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:index-pointing-up" /></template>
<style>
.aqdvvfb8n {
  width: 1.936px;
  height: 4.588px;
  x: 7.459px;
  y: 13.89px;
  fill: var(--svg-color--ffdf64, #FFDF64);
  rx: 0.968px;
}

.ay4016bbi {
  stop-color: var(--svg-color--d6980b, #D6980B);
}

.b0wns5brh {
  stop-color: var(--svg-color--ffdf64, #FFDF64);
  stop-opacity: 0;
}

.dfytqvbtn {
  d: path("M22.41 1.906a2.656 2.656 0 0 0-2.657 2.657v11.25H4.958v4.227c0 5.553 4.501 10.054 10.054 10.054c4.243 0 7.872-2.629 9.348-6.347l.003.003c1.015-2.39 1.015-6.703.843-7.86c-.104-.7-.133-1.205-.14-1.496V4.563a2.656 2.656 0 0 0-2.656-2.657");
}

.dqdy8qbll {
  stop-color: var(--svg-color--ffe652, #FFE652);
}

.dy9bgzbsh {
  fill: var(--svg-color--de6c2a, #DE6C2A);
  d: path("M10.448 15.658c0-1.294 1.08-2.343 2.413-2.343s2.413 1.049 2.413 2.343v3.062c0 1.294-1.08 2.343-2.413 2.343s-2.218-.672-2.218-2.084z");
}

.dyr_s7bji {
  stop-color: var(--svg-color--c4811c, #C4811C);
  stop-opacity: 0;
}

.dyzapwyss {
  fill: var(--svg-color--de6c2a, #DE6C2A);
  d: path("M6.597 16.103c0-1.057.842-1.844 1.913-1.913c.996-.048 1.986.563 2.07 1.776l.165 2.303c.083 1.155-.994 2.137-2.152 2.137a1.996 1.996 0 0 1-1.996-1.995z");
}

.f1d5fxxtc {
  stop-color: var(--svg-color--d6980b, #D6980B);
  stop-opacity: 0;
}

.fq034wb8i {
  stop-color: var(--svg-color--fa8f57, #FA8F57);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvqz7gbma {
  d: path("M4.958 14.6c0-1.382 1.102-2.412 2.502-2.502c1.303-.063 2.597.735 2.707 2.323l.216 3.013c.108 1.51-1.3 2.796-2.815 2.796a2.61 2.61 0 0 1-2.61-2.61z");
}

.glp6n8btl {
  stop-color: var(--svg-color--ffe465, #FFE465);
  stop-opacity: 0;
}

.h3qumrbim {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M18.262 17.11c1.202 0 3.21 0 3.946.944c1.076 1.052 1.138 2.589 1.198 3.009");
}

.iw0ta6tlw {
  stop-color: var(--svg-color--f1910b, #F1910B);
}

.j_u2hgojt {
  stop-color: var(--svg-color--ffde44, #FFDE44);
}

.j5djnfbxg {
  stop-color: var(--svg-color--ffe465, #FFE465);
}

.jagc-vbbt {
  stop-color: var(--svg-color--c4811c, #C4811C);
}

.jmrhb8bgs {
  stop-color: var(--svg-color--ffeb65, #FFEB65);
}

.jwnwrcbqf {
  stop-color: var(--svg-color--feb634, #FEB634);
}

.kbivl4mwv {
  stop-color: var(--svg-color--ffb451, #FFB451);
}

.m8a52jbjp {
  stop-color: var(--svg-color--fcc52a, #FCC52A);
}

.m8cr0gb9p {
  d: path("M14.936 13.008c0-1.574 1.212-2.85 2.707-2.85s2.707 1.276 2.707 2.85v3.727c0 1.574-1.212 2.85-2.707 2.85s-2.707-.732-2.707-2.45z");
}

.n6e81rbnm {
  d: path("M9.805 13.502a2.636 2.636 0 0 1 5.273 0v3.447a2.636 2.636 0 0 1-2.637 2.636c-1.456 0-2.423-.756-2.423-2.345z");
}

.ni_pyug7k {
  stop-color: var(--svg-color--ffc734, #FFC734);
}

.nz3671a2d {
  stop-color: var(--svg-color--ffde44, #FFDE44);
  stop-opacity: 0;
}

.o-cktxbbz {
  stop-color: var(--svg-color--f5936e, #F5936E);
  stop-opacity: 0;
}

.pz6alqb9u {
  stop-color: var(--svg-color--ffeb65, #FFEB65);
  stop-opacity: 0;
}

.rfm1mc8uy {
  stop-color: var(--svg-color--f1910b, #F1910B);
  stop-opacity: 0;
}

.rna5z7w0d {
  fill: var(--svg-color--ffb451, #FFB451);
  d: path("M22.41 1.906a2.656 2.656 0 0 0-2.657 2.657v11.25H4.958v4.227c0 5.553 4.501 10.054 10.054 10.054c4.243 0 7.872-2.629 9.348-6.347l.003.003c1.015-2.39 1.015-6.703.843-7.86c-.104-.7-.133-1.205-.14-1.496V4.563a2.656 2.656 0 0 0-2.656-2.657");
}

.shz-33bia {
  stop-color: var(--svg-color--ffdf64, #FFDF64);
}

.sz1do8gnu {
  width: 1.688px;
  height: 11.594px;
  x: 22.469px;
  y: 3.531px;
  fill: var(--svg-color--ffea5f, #FFEA5F);
  rx: 0.844px;
}

.t4xzuwzej {
  stop-color: var(--svg-color--ffe242, #FFE242);
}

.tdl82ibjz {
  stop-color: var(--svg-color--f5bc28, #F5BC28);
}

.tsclx3b3b {
  fill: var(--svg-color--de6c2a, #DE6C2A);
  d: path("M14.031 18.875c0-1.433 1.125-2.594 2.512-2.594l2.316.11c.346.042.69.14 1.007.288c1.91.805 3.39 2.644 3.681 4.805h-6.585a3 3 0 0 0-.313-.015h-.106c-1.387 0-2.512-1.162-2.512-2.594");
}

.vq0_sbcit {
  stop-color: var(--svg-color--ffe652, #FFE652);
  stop-opacity: 0;
}

.w_i9pivku {
  width: 2.422px;
  height: 6.02px;
  x: 17.402px;
  y: 11.489px;
  fill: var(--svg-color--ffdf64, #FFDF64);
  rx: 1.211px;
}

.wdfzl_kyi {
  stop-color: var(--svg-color--f5936e, #F5936E);
}

.wolgahxqu {
  stop-color: var(--svg-color--ffb451, #FFB451);
  stop-opacity: 0;
}

.wxce1m7zf {
  d: path("M17.543 15.281c-1.387 0-2.512 1.161-2.512 2.594s1.125 2.594 2.512 2.594h.106c.821 0 1.64.317 2.066 1.02a6 6 0 0 1 .875 3.136c0 .878-.187 1.712-.522 2.463c2.599-.625 4.532-2.995 4.532-5.822c0-2.492-1.597-4.686-3.734-5.587a3.4 3.4 0 0 0-1.007-.288z");
}

.x5_tf7bfb {
  stop-color: var(--svg-color--fa8f57, #FA8F57);
}

.xv0941b3r {
  stop-color: var(--svg-color--ffd92a, #FFD92A);
}

.ygez98-kq {
  width: 1.936px;
  height: 5.303px;
  x: 12.141px;
  y: 11.807px;
  rx: 0.968px;
}

.zir7o27xr {
  stop-color: var(--svg-color--ffb342, #FFB342);
}

.znr-lcc7s {
  stop-color: var(--svg-color--f6a218, #F6A218);
}

</style>
