<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ixesQ6d)"><path fill="url(#iIssBNd)" class="nekxlu6vv"/><path fill="url(#ihFyROW)" class="nekxlu6vv"/><path fill="url(#i8RDZ7d)" class="nekxlu6vv"/><path fill="url(#i1Ajw2b)" class="nekxlu6vv"/></g><g filter="url(#iISbwHf)"><path fill="url(#io88CVd)" class="a2ix4_xti"/></g><g filter="url(#iktJRrb)"><path stroke="url(#iL3TCee)" class="a0csagq-i"/></g><path fill="url(#igSptQe)" class="cowdq1brr"/><path fill="url(#iMTjQtd)" class="cowdq1brr"/><defs><radialGradient id="ihFyROW" cx="0" cy="0" r="1" gradientTransform="rotate(106.909 -4.108 14.386)scale(4.08276 7.23265)" gradientUnits="userSpaceOnUse"><stop class="y8vsu5ztk"/><stop offset="1" class="rgrkf768n"/></radialGradient><radialGradient id="i1Ajw2b" cx="0" cy="0" r="1" gradientTransform="rotate(-60.289 40.223 .376)scale(13.2407 37.8141)" gradientUnits="userSpaceOnUse"><stop offset=".685" class="jtx_0kbqd"/><stop offset="1" class="zym8q2i6h"/></radialGradient><radialGradient id="iL3TCee" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 -1.40625 13.30211 4.13843 9.274 25.219)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="z77bu1b7u"/><stop offset="1" class="kz2ndtery"/></radialGradient><radialGradient id="igSptQe" cx="0" cy="0" r="1" gradientTransform="matrix(1.0625 -3.5 5.71548 1.73506 15.149 26.625)" gradientUnits="userSpaceOnUse"><stop class="vt318cb4p"/><stop offset="1" class="orouewb7m"/></radialGradient><linearGradient id="iIssBNd" x1="7.68" x2="18.336" y1="25.031" y2="29.719" gradientUnits="userSpaceOnUse"><stop class="i6tauqxqr"/><stop offset="1" class="zp3twcb7d"/></linearGradient><linearGradient id="i8RDZ7d" x1="1.867" x2="5.805" y1="25.813" y2="25.813" gradientUnits="userSpaceOnUse"><stop class="ew6c_346z"/><stop offset="1" class="vza-7rh6h"/></linearGradient><linearGradient id="io88CVd" x1="2.774" x2="10.024" y1="29.313" y2="29.313" gradientUnits="userSpaceOnUse"><stop class="kjg13vjbg"/><stop offset="1" class="p75py3m3m"/></linearGradient><linearGradient id="iMTjQtd" x1="22.117" x2="17.836" y1="25.813" y2="26.781" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rebucf2ax"/><stop offset="1" class="sza3r4xog"/></linearGradient><filter id="ixesQ6d" width="27.906" height="9.088" x="2.047" y="20.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.364706 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17265"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.364706 0 0 0 0 0.815686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_17265" result="effect2_innerShadow_18_17265"/></filter><filter id="iISbwHf" width="8.13" height="2.284" x="2.094" y="27.706" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.368627 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17265"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.105882 0 0 0 0 0.223529 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_17265" result="effect2_innerShadow_18_17265"/></filter><filter id="iktJRrb" width="19.942" height="7.052" x="3.233" y="20.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17265" stdDeviation=".1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:flat-shoe" /></template>
<style>
.a0csagq-i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m3.612 20.948l-.08.017v.081c0 .514.259 1.33 1.302 1.704c1.15.413 8.97 3.11 12.735 4.407c1.187.409 3.022.3 4.377-1.44l.95-1.22l-.132-.148q-.135.082-.26.184q-.244.197-.525.419c-.64.476-1.477.652-2.275.674a6.9 6.9 0 0 1-1.979-.237L4.717 21.014a2.1 2.1 0 0 0-1.105-.066Z");
}

.a2ix4_xti {
  d: path("M2.094 27.906h7.93v1.635a.35.35 0 0 1-.35.35h-7.23a.35.35 0 0 1-.35-.35z");
}

.cowdq1brr {
  d: path("M3.633 21.046c0 .482.24 1.254 1.234 1.61c1.15.413 8.97 3.11 12.735 4.407c1.154.397 2.94.293 4.265-1.407q.535-.685.95-1.221q-.13.077-.25.176q-.244.199-.528.42c-1.325.988-3.448.714-4.344.453L4.685 21.11a2 2 0 0 0-1.052-.063");
}

.ew6c_346z {
  stop-color: var(--svg-color--4a9cdc, #4A9CDC);
}

.ft5dv1b6b {
  fill: none;
}

.i6tauqxqr {
  stop-color: var(--svg-color--3dacff, #3DACFF);
}

.jtx_0kbqd {
  stop-color: var(--svg-color--66baff, #66BAFF);
  stop-opacity: 0;
}

.kjg13vjbg {
  stop-color: var(--svg-color--276aa5, #276AA5);
}

.kz2ndtery {
  stop-color: var(--svg-color--5ac7ff, #5AC7FF);
  stop-opacity: 0;
}

.nekxlu6vv {
  d: path("m2.047 23.027l.055 4.88h9.528c.413 0 .799.203 1.032.543l.689 1.006a1 1 0 0 0 .825.435h15.438a.29.29 0 0 0 .291-.25c.34-2.613-1.203-3.797-2.475-4.297l-2.686-1.073a2.16 2.16 0 0 0-2.177.34q-.244.199-.528.42c-1.325.988-3.448.714-4.344.453L4.685 21.11a2 2 0 0 0-2.638 1.918");
}

.orouewb7m {
  stop-color: var(--svg-color--2865a8, #2865A8);
}

.p75py3m3m {
  stop-color: var(--svg-color--2765ad, #2765AD);
}

.rebucf2ax {
  stop-color: var(--svg-color--214f89, #214F89);
}

.rgrkf768n {
  stop-color: var(--svg-color--59c2ff, #59C2FF);
  stop-opacity: 0;
}

.sza3r4xog {
  stop-color: var(--svg-color--214f89, #214F89);
  stop-opacity: 0;
}

.vt318cb4p {
  stop-color: var(--svg-color--2775cc, #2775CC);
}

.vza-7rh6h {
  stop-color: var(--svg-color--4a9cdc, #4A9CDC);
  stop-opacity: 0;
}

.y8vsu5ztk {
  stop-color: var(--svg-color--59c2ff, #59C2FF);
}

.z77bu1b7u {
  stop-color: var(--svg-color--5ac7ff, #5AC7FF);
}

.zp3twcb7d {
  stop-color: var(--svg-color--44a2fd, #44A2FD);
}

.zym8q2i6h {
  stop-color: var(--svg-color--66baff, #66BAFF);
}

</style>
