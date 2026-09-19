<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iM5WXhe)"><path fill="url(#imO6lWb)" class="gild1vbfy"/></g><g filter="url(#iP28TMd)"><path class="o6tn57zpe"/></g><g filter="url(#iEigOKb)"><path fill="url(#iYjX4Fd)" class="ljw8f03ot"/></g><g filter="url(#iZ2hCCb)"><path class="rz_9ldb3v"/><path fill="url(#igfFmFk)" class="wvs5w5wzl"/><path fill="url(#i3Qe6Ce)" class="wvs5w5wzl"/></g><g filter="url(#i9ZfjHe)"><path class="zeeu5kbzt"/><path fill="url(#iPndVvb)" class="zsgynmv6t"/><path fill="url(#iHawZpb)" class="zsgynmv6t"/></g><g filter="url(#iPDYVLc)"><path fill="url(#ihqX0sb)" class="raj09sbvd"/></g><g filter="url(#i8cwtId)"><path fill="url(#izS8kub)" class="ges1v2jzs"/></g><g filter="url(#ibAkG4d)"><path fill="url(#i1WxAPb)" class="kkozepy5z"/></g><g filter="url(#iVv0Aqc)"><path fill="url(#iCVQ3kc)" class="u-8ygpbhi"/></g><g filter="url(#idYasmX)"><path fill="url(#iX6utle)" class="qjvdzhjtl"/></g><g filter="url(#icIb54c)"><circle class="viu2bocco"/></g><g filter="url(#ibcnLnd)"><circle class="cdtm5d_3u"/></g><path fill="url(#iTDbKQc)" class="xa8gh3b0e"/><path fill="url(#iCq7oIe)" class="muean4bfe"/><defs><filter id="iM5WXhe" width="28.325" height="19.474" x="1.862" y="10.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.188235 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22880"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.439216 0 0 0 0 0.713726 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_22880" result="effect2_innerShadow_18_22880"/></filter><filter id="iP28TMd" width="19.203" height="4.746" x="5.639" y="10.651" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22880" stdDeviation=".375"/></filter><filter id="iEigOKb" width="19.203" height="14.257" x="5.639" y="13.897" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22880" stdDeviation=".375"/></filter><filter id="iZ2hCCb" width="18.294" height="12.169" x="6.773" y="14.976" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.568627 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22880"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_22880" result="effect2_innerShadow_18_22880"/></filter><filter id="i9ZfjHe" width="18.294" height="12.169" x="6.851" y="1.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.568627 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22880"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_22880" result="effect2_innerShadow_18_22880"/></filter><filter id="iPDYVLc" width="5.98" height="7.009" x="9.045" y="3.963" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.505882 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22880"/></filter><filter id="i8cwtId" width="6.089" height="1.058" x="16.951" y="3.963" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.545098 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22880"/></filter><filter id="ibAkG4d" width="6.089" height="1.058" x="16.951" y="5.955" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.545098 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22880"/></filter><filter id="iVv0Aqc" width="6.089" height="1.058" x="16.951" y="7.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.545098 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22880"/></filter><filter id="idYasmX" width="6.089" height="1.058" x="16.951" y="9.914" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.592157 0 0 0 0 0.545098 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22880"/></filter><filter id="icIb54c" width="1.878" height="1.878" x="9.348" y="15.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22880" stdDeviation=".2"/></filter><filter id="ibcnLnd" width="1.878" height="1.878" x="20.301" y="15.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22880" stdDeviation=".2"/></filter><linearGradient id="imO6lWb" x1="16" x2="16" y1="10.972" y2="29.372" gradientUnits="userSpaceOnUse"><stop class="j87bfgb5c"/><stop offset="1" class="xt3a8gbvf"/></linearGradient><linearGradient id="iYjX4Fd" x1="15.241" x2="15.241" y1="14.647" y2="27.404" gradientUnits="userSpaceOnUse"><stop class="nfeudyb3m"/><stop offset="1" class="w93lh82tg"/></linearGradient><linearGradient id="ihqX0sb" x1="12.01" x2="12.01" y1="4.013" y2="10.972" gradientUnits="userSpaceOnUse"><stop class="icwu6aczt"/><stop offset="1" class="f09sies8m"/></linearGradient><linearGradient id="izS8kub" x1="19.971" x2="19.971" y1="4.013" y2="5.021" gradientUnits="userSpaceOnUse"><stop class="f57xpmb8q"/><stop offset="1" class="f57xpmb8q"/></linearGradient><linearGradient id="i1WxAPb" x1="19.971" x2="19.971" y1="6.005" y2="7.013" gradientUnits="userSpaceOnUse"><stop class="f57xpmb8q"/><stop offset="1" class="f57xpmb8q"/></linearGradient><linearGradient id="iCVQ3kc" x1="19.971" x2="19.971" y1="7.95" y2="8.958" gradientUnits="userSpaceOnUse"><stop class="f57xpmb8q"/><stop offset="1" class="f57xpmb8q"/></linearGradient><linearGradient id="iX6utle" x1="19.971" x2="19.971" y1="9.964" y2="10.972" gradientUnits="userSpaceOnUse"><stop class="f57xpmb8q"/><stop offset="1" class="f57xpmb8q"/></linearGradient><radialGradient id="igfFmFk" cx="0" cy="0" r="1" gradientTransform="matrix(-1.14062 -2.28084 .73708 -.3686 9.81 16.029)" gradientUnits="userSpaceOnUse"><stop class="qfrnpfazk"/><stop offset="1" class="qgd--y8yh"/></radialGradient><radialGradient id="i3Qe6Ce" cx="0" cy="0" r="1" gradientTransform="matrix(-.6875 -1.59375 .51504 -.22217 20.858 16.122)" gradientUnits="userSpaceOnUse"><stop offset=".137" class="qfrnpfazk"/><stop offset="1" class="qgd--y8yh"/></radialGradient><radialGradient id="iPndVvb" cx="0" cy="0" r="1" gradientTransform="matrix(-.75001 1.76563 -.85697 -.36403 21.077 13.044)" gradientUnits="userSpaceOnUse"><stop offset=".134" class="aqohfl02a"/><stop offset="1" class="nh3v8ubbj"/></radialGradient><radialGradient id="iHawZpb" cx="0" cy="0" r="1" gradientTransform="rotate(117.588 1.136 9.582)scale(1.95687 .94979)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="aqohfl02a"/><stop offset="1" class="nh3v8ubbj"/></radialGradient><radialGradient id="iTDbKQc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.125 -.80618 0 11.069 13.685)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="upsdv1q6s"/><stop offset="1" class="rdoxplxgw"/></radialGradient><radialGradient id="iCq7oIe" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.125 -.80618 0 21.975 13.685)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="upsdv1q6s"/><stop offset="1" class="rdoxplxgw"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:card-index" /></template>
<style>
.aqohfl02a {
  stop-color: var(--svg-color--998ba6, #998BA6);
}

.cdtm5d_3u {
  cx: 21.241px;
  cy: 16.693px;
  r: 0.539px;
  fill: var(--svg-color--9d8bae, #9D8BAE);
}

.f09sies8m {
  stop-color: var(--svg-color--3e82d6, #3E82D6);
}

.f57xpmb8q {
  stop-color: var(--svg-color--a69eae, #A69EAE);
}

.ft5dv1b6b {
  fill: none;
}

.ges1v2jzs {
  d: path("M16.951 4.517c0-.278.226-.504.504-.504h5.032a.504.504 0 0 1 0 1.008h-5.032a.504.504 0 0 1-.504-.504");
}

.gild1vbfy {
  d: path("M3.962 10.972a1.9 1.9 0 0 0-1.9 1.9v3.467a2 2 0 0 0 1.558 1.95c.211.049.385.222.385.438v8.07a3.2 3.2 0 0 0 3.2 3.2h17.59a3.2 3.2 0 0 0 3.2-3.2v-8.07c0-.216.174-.39.385-.437a2 2 0 0 0 1.558-1.951v-3.467a1.9 1.9 0 0 0-1.9-1.9z");
}

.icwu6aczt {
  stop-color: var(--svg-color--3eadff, #3EADFF);
}

.j87bfgb5c {
  stop-color: var(--svg-color--5a4d99, #5A4D99);
}

.kkozepy5z {
  d: path("M16.951 6.509c0-.278.226-.504.504-.504h5.032a.504.504 0 1 1 0 1.008h-5.032a.504.504 0 0 1-.504-.504");
}

.ljw8f03ot {
  d: path("M6.389 25.404a2 2 0 0 0 2 2h13.703a2 2 0 0 0 2-2v-8.757a2 2 0 0 0-2-2H8.389a2 2 0 0 0-2 2z");
}

.muean4bfe {
  d: path("M20.975 12.45a.5.5 0 1 1 1 0v4.086a.5.5 0 0 1-1 0z");
}

.nfeudyb3m {
  stop-color: var(--svg-color--402a5d, #402A5D);
}

.nh3v8ubbj {
  stop-color: var(--svg-color--e0d6e9, #E0D6E9);
  stop-opacity: 0;
}

.o6tn57zpe {
  fill: var(--svg-color--3f3170, #3F3170);
  d: path("M6.389 11.4h17.703v1.247a2 2 0 0 1-2 2H8.389a2 2 0 0 1-2-2z");
}

.qfrnpfazk {
  stop-color: var(--svg-color--c0b2cf, #C0B2CF);
}

.qgd--y8yh {
  stop-color: var(--svg-color--e0d6ea, #E0D6EA);
  stop-opacity: 0;
}

.qjvdzhjtl {
  d: path("M16.951 10.468c0-.278.226-.504.504-.504h5.032a.504.504 0 0 1 0 1.008h-5.032a.504.504 0 0 1-.504-.504");
}

.raj09sbvd {
  d: path("M9.045 4.763a.75.75 0 0 1 .75-.75h4.43a.75.75 0 0 1 .75.75v5.46a.75.75 0 0 1-.75.75h-4.43a.75.75 0 0 1-.75-.75z");
}

.rdoxplxgw {
  stop-color: var(--svg-color--2c2242, #2C2242);
}

.rz_9ldb3v {
  fill: var(--svg-color--dfd5e9, #DFD5E9);
  d: path("M6.873 16.726c0-.911.739-1.65 1.65-1.65h14.794c.911 0 1.65.739 1.65 1.65v8.669a1.65 1.65 0 0 1-1.65 1.65H8.523a1.65 1.65 0 0 1-1.65-1.65z");
}

.u-8ygpbhi {
  d: path("M16.951 8.454c0-.278.226-.504.504-.504h5.032a.504.504 0 0 1 0 1.008h-5.032a.504.504 0 0 1-.504-.504");
}

.upsdv1q6s {
  stop-color: var(--svg-color--433e58, #433E58);
}

.viu2bocco {
  cx: 10.287px;
  cy: 16.693px;
  r: 0.539px;
  fill: var(--svg-color--9d8bae, #9D8BAE);
}

.w93lh82tg {
  stop-color: var(--svg-color--3f2e62, #3F2E62);
}

.wvs5w5wzl {
  d: path("M6.873 16.726c0-.911.739-1.65 1.65-1.65h14.794c.911 0 1.65.739 1.65 1.65v8.669a1.65 1.65 0 0 1-1.65 1.65H8.523a1.65 1.65 0 0 1-1.65-1.65z");
}

.xa8gh3b0e {
  d: path("M10.069 12.45a.5.5 0 0 1 1 0v4.086a.5.5 0 0 1-1 0z");
}

.xt3a8gbvf {
  stop-color: var(--svg-color--583f79, #583F79);
}

.zeeu5kbzt {
  fill: var(--svg-color--dfd5e9, #DFD5E9);
  d: path("M6.951 3.71c0-.911.74-1.65 1.65-1.65h14.794c.911 0 1.65.739 1.65 1.65v8.669a1.65 1.65 0 0 1-1.65 1.65H8.601a1.65 1.65 0 0 1-1.65-1.65z");
}

.zsgynmv6t {
  d: path("M6.951 3.71c0-.911.74-1.65 1.65-1.65h14.794c.911 0 1.65.739 1.65 1.65v8.669a1.65 1.65 0 0 1-1.65 1.65H8.601a1.65 1.65 0 0 1-1.65-1.65z");
}

</style>
