<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iBEeoFl)"><path fill="url(#iJv9U0b)" class="gh69tcbiy"/><path fill="url(#iE7Bvwd)" class="gh69tcbiy"/></g><g filter="url(#ia0yS6H)"><path class="wcvyh_6cv"/></g><g filter="url(#iJnVkQd)"><path stroke="url(#i6lXt5b)" class="z-mdy21uz"/></g><path fill="url(#ifVNehZ)" class="pffu9epai"/><g filter="url(#istasxe)"><path fill="url(#iIaGa6b)" class="lq4_48rfq"/><path fill="url(#iG3yDDh)" class="lq4_48rfq"/></g><path fill="url(#iMlVBie)" class="u0p21231g"/><path fill="url(#iBGz1nx)" class="u0p21231g"/><g filter="url(#iukxUWd)"><path fill="url(#ihFnoZc)" class="qe286_pol"/></g><g filter="url(#iukxUWd)"><path fill="url(#ihFnoZc)" class="qe286_pol"/></g><path fill="url(#isordib)" class="qe286_pol"/><path fill="url(#iq2D9Xd)" class="qe286_pol"/><g filter="url(#iHsLmmb)"><path stroke="url(#idSk1se)" class="tgo-sbb5l"/></g><g filter="url(#iL1Pm6d)"><path class="b-yj7zbdo"/></g><g filter="url(#ivFyE9V)"><path stroke="url(#i2kKHub)" class="qud21rbli"/></g><g filter="url(#iFu5dYb)"><path stroke="url(#iOkEwvd)" class="kwsnx8k1o"/></g><g filter="url(#iZ1nMqc)"><path stroke="url(#iqRIkMc)" class="txu1c_bnx"/></g><g filter="url(#iwvLLRd)"><path stroke="url(#ihFSLOc)" class="d-uauibsk"/></g><defs><filter id="iBEeoFl" width="15.06" height="21.972" x="14.941" y="8.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670833 0 0 0 0 0.167708 0 0 0 0 0.17557 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7955"/></filter><filter id="ia0yS6H" width="12.591" height="18.451" x="17.018" y="7.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7955" stdDeviation=".5"/></filter><filter id="iJnVkQd" width="4.356" height="15.387" x="25.462" y="9.338" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7955" stdDeviation=".2"/></filter><filter id="istasxe" width="15.051" height="10.5" x="5.88" y="1.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.4 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7955"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.521569 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_28327_7955" result="effect2_innerShadow_28327_7955"/></filter><filter id="iukxUWd" width="10.001" height="7" x="2" y="17.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.372549 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7955"/></filter><filter id="iHsLmmb" width="7.769" height="6.831" x="4.319" y="16.975" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7955" stdDeviation=".2"/></filter><filter id="iL1Pm6d" width="7.614" height="4.654" x="5.792" y="19.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.505882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7955"/></filter><filter id="ivFyE9V" width="11.325" height="20.512" x="18.697" y="4.119" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7955" stdDeviation=".2"/></filter><filter id="iFu5dYb" width="7.312" height="4.29" x="5.993" y="19.366" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7955" stdDeviation=".125"/></filter><filter id="iZ1nMqc" width="13.022" height="7.577" x="4.218" y="4.312" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7955" stdDeviation=".125"/></filter><filter id="iwvLLRd" width="2.749" height="5.712" x="17.817" y="2.255" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7955" stdDeviation=".125"/></filter><radialGradient id="iJv9U0b" cx="0" cy="0" r="1" gradientTransform="rotate(113.962 8.316 14.561)scale(14.1577 14.0245)" gradientUnits="userSpaceOnUse"><stop class="fru9jxb9k"/><stop offset=".931" class="i3o86bcbu"/></radialGradient><radialGradient id="iE7Bvwd" cx="0" cy="0" r="1" gradientTransform="matrix(3.125 0 0 11.125 14 25.125)" gradientUnits="userSpaceOnUse"><stop class="pdqbq7pwd"/><stop offset="1" class="s2l507-2z"/></radialGradient><radialGradient id="iIaGa6b" cx="0" cy="0" r="1" gradientTransform="matrix(-9.0972 4.89322 -5.31775 -9.88647 18.364 5.593)" gradientUnits="userSpaceOnUse"><stop class="l7jses28p"/><stop offset="1" class="ujxp8fbqa"/></radialGradient><radialGradient id="iG3yDDh" cx="0" cy="0" r="1" gradientTransform="rotate(-153.023 10.025 3.286)scale(4.55775 10.0653)" gradientUnits="userSpaceOnUse"><stop class="alid8n-ci"/><stop offset="1" class="w8x7ksbvx"/></radialGradient><radialGradient id="iBGz1nx" cx="0" cy="0" r="1" gradientTransform="matrix(-.651 .53638 -.51895 -.62985 17.32 4.427)" gradientUnits="userSpaceOnUse"><stop class="mnzuvd9mw"/><stop offset="1" class="kf479hobq"/></radialGradient><radialGradient id="ihFnoZc" cx="0" cy="0" r="1" gradientTransform="rotate(143.368 2.074 12.065)scale(4.90635 7.89611)" gradientUnits="userSpaceOnUse"><stop class="jwbyb7b4i"/><stop offset="1" class="wx648tb2b"/></radialGradient><radialGradient id="isordib" cx="0" cy="0" r="1" gradientTransform="matrix(-2 1.84375 -8.1052 -8.79214 11.25 19.594)" gradientUnits="userSpaceOnUse"><stop class="vsqf78kmo"/><stop offset="1" class="x9jisjb_u"/></radialGradient><radialGradient id="iq2D9Xd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.53148 -2.125 .87567 -1.04318 7 21.031)" gradientUnits="userSpaceOnUse"><stop class="m7_yw6bmd"/><stop offset="1" class="m-o_1bb9y"/></radialGradient><linearGradient id="i6lXt5b" x1="30.081" x2="18.201" y1="10.466" y2="14.878" gradientUnits="userSpaceOnUse"><stop class="vllpc8b7z"/><stop offset="1" class="i925jlbls"/></linearGradient><linearGradient id="ifVNehZ" x1="30.02" x2="16.017" y1="10.375" y2="29.666" gradientUnits="userSpaceOnUse"><stop class="irfq5zwwm"/><stop offset="1" class="j2c1bwb7f"/></linearGradient><linearGradient id="iMlVBie" x1="4.813" x2="15.875" y1="12.375" y2="3.813" gradientUnits="userSpaceOnUse"><stop class="yb3xhwbhy"/><stop offset="1" class="gj35r8buv"/><stop offset="1" class="o_fvhubvn"/></linearGradient><linearGradient id="idSk1se" x1="9.351" x2="5.14" y1="18.21" y2="17.5" gradientUnits="userSpaceOnUse"><stop class="fprj15bei"/><stop offset="1" class="kpanlurvh"/></linearGradient><linearGradient id="i2kKHub" x1="32.188" x2="7.633" y1="5.438" y2="26.931" gradientUnits="userSpaceOnUse"><stop class="c95kzlbib"/><stop offset="1" class="l6-5zucds"/></linearGradient><linearGradient id="iOkEwvd" x1="7.549" x2="14.606" y1="19.914" y2="25.637" gradientUnits="userSpaceOnUse"><stop class="vkxkfbb-b"/><stop offset="1" class="r9qmfnx3l"/></linearGradient><linearGradient id="iqRIkMc" x1="16.588" x2="6.018" y1="5.402" y2="10.954" gradientUnits="userSpaceOnUse"><stop class="f40bqfejw"/><stop offset="1" class="i_njx8bpv"/></linearGradient><linearGradient id="ihFSLOc" x1="20.431" x2="18.936" y1="2.475" y2="2.708" gradientUnits="userSpaceOnUse"><stop class="jx4lap87d"/><stop offset="1" class="myz0_9hux"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:fallen-leaf" /></template>
<style>
.alid8n-ci {
  stop-color: var(--svg-color--dd763b, #DD763B);
}

.b-yj7zbdo {
  fill: var(--svg-color--d55b3e, #D55B3E);
  d: path("M12.896 23.02h-.63c-.48 0-.94-.15-1.33-.43l-4.26-3.04a.483.483 0 0 0-.68.11s0 .01-.01.01c-.16.22-.11.53.11.69l4.26 3.04c.56.4 1.22.61 1.91.61h.64c.29 0 .51-.24.5-.53a.51.51 0 0 0-.51-.46");
}

.c95kzlbib {
  stop-color: var(--svg-color--c16073, #C16073);
}

.d-uauibsk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M20.19 2.63c-.046.815-.51 2.95-1.998 4.962");
}

.f40bqfejw {
  stop-color: var(--svg-color--f18546, #F18546);
}

.fprj15bei {
  stop-color: var(--svg-color--efa55a, #EFA55A);
}

.fru9jxb9k {
  stop-color: var(--svg-color--bb3f4a, #BB3F4A);
}

.ft5dv1b6b {
  fill: none;
}

.gh69tcbiy {
  d: path("M27.91 8.01c-7.13 0-12.91 5.78-12.97 12.66l.06 8.57c0 .43.37.77.79.74C23.71 29.57 30 23.03 30 15.01v-7z");
}

.gj35r8buv {
  stop-color: var(--svg-color--dc7c28, #DC7C28);
}

.i_njx8bpv {
  stop-color: var(--svg-color--f18546, #F18546);
  stop-opacity: 0;
}

.i3o86bcbu {
  stop-color: var(--svg-color--d75a43, #D75A43);
}

.i925jlbls {
  stop-color: var(--svg-color--d35d5c, #D35D5C);
  stop-opacity: 0;
}

.irfq5zwwm {
  stop-color: var(--svg-color--a52344, #A52344);
}

.j2c1bwb7f {
  stop-color: var(--svg-color--c03c49, #C03C49);
}

.jwbyb7b4i {
  stop-color: var(--svg-color--e4903b, #E4903B);
}

.jx4lap87d {
  stop-color: var(--svg-color--f89d66, #F89D66);
}

.kf479hobq {
  stop-color: var(--svg-color--ea9759, #EA9759);
  stop-opacity: 0;
}

.kpanlurvh {
  stop-color: var(--svg-color--efa55a, #EFA55A);
  stop-opacity: 0;
}

.kwsnx8k1o {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m6.368 19.741l4.1 2.97a3 3 0 0 0 1.76.57h.702");
}

.l6-5zucds {
  stop-color: var(--svg-color--c16073, #C16073);
  stop-opacity: 0;
}

.l7jses28p {
  stop-color: var(--svg-color--e2773a, #E2773A);
}

.lq4_48rfq {
  d: path("M6.13 10.62c0-4.72 3.83-8.57 8.39-8.61L20.19 2c.28 0 .51.24.49.53c-.27 5.23-4.61 9.47-9.92 9.47H6.13z");
}

.m-o_1bb9y {
  stop-color: var(--svg-color--da6a3b, #DA6A3B);
  stop-opacity: 0;
}

.m7_yw6bmd {
  stop-color: var(--svg-color--da6a3b, #DA6A3B);
}

.mnzuvd9mw {
  stop-color: var(--svg-color--ea9759, #EA9759);
}

.myz0_9hux {
  stop-color: var(--svg-color--f89d66, #F89D66);
  stop-opacity: 0;
}

.o_fvhubvn {
  stop-color: var(--svg-color--dd7e24, #DD7E24);
}

.pdqbq7pwd {
  stop-color: var(--svg-color--be412d, #BE412D);
}

.pffu9epai {
  d: path("M19.06 24.92a.753.753 0 0 1-.61-1.19l9.768-13.623c.238-.311.293-.574.293-1.013L28.5 4.76a.749.749 0 1 1 1.5 0l.02 4.749c0 .5-.326 1.073-.534 1.354L19.681 24.61c-.15.2-.38.31-.62.31");
}

.qe286_pol {
  d: path("M12 22.93c0-3.24-2.63-5.89-5.76-5.91l-3.9-.01c-.2 0-.35.17-.34.36c.19 3.6 3.17 6.64 6.82 6.64H12z");
}

.qud21rbli {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M29.422 4.719v3.93a4 4 0 0 1-.751 2.334l-9.374 13.048");
}

.r9qmfnx3l {
  stop-color: var(--svg-color--e6894f, #E6894F);
  stop-opacity: 0;
}

.s2l507-2z {
  stop-color: var(--svg-color--be412d, #BE412D);
  stop-opacity: 0;
}

.tgo-sbb5l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M4.844 17.5h1.562c.688.063 2.35.462 3.5 1.563c1.438 1.375 1.656 3.093 1.656 4.218");
}

.txu1c_bnx {
  stroke-linecap: round;
  stroke-opacity: 0.5;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M4.593 11.514h1.606a4 4 0 0 0 2.357-.768l8.309-6.059");
}

.u0p21231g {
  d: path("M17.32 4.76a.497.497 0 0 0-.78-.41l-8.75 6.24c-.39.28-.85.43-1.33.43H4.5c-.28 0-.5.22-.5.49s.22.5.5.5h1.96c.69 0 1.35-.21 1.91-.61l8.74-6.23c.14-.1.21-.25.21-.41");
}

.ujxp8fbqa {
  stop-color: var(--svg-color--dc8839, #DC8839);
}

.vkxkfbb-b {
  stop-color: var(--svg-color--e6894f, #E6894F);
}

.vllpc8b7z {
  stop-color: var(--svg-color--d35d5c, #D35D5C);
}

.vsqf78kmo {
  stop-color: var(--svg-color--e38f3c, #E38F3C);
}

.w8x7ksbvx {
  stop-color: var(--svg-color--dd763b, #DD763B);
  stop-opacity: 0;
}

.wcvyh_6cv {
  fill: var(--svg-color--c34749, #C34749);
  d: path("M18.32 24.983a.72.72 0 0 0 .992-.16L28.22 12.33q.222-.315.39-.656v-3.01h-.95l.003.934a3.27 3.27 0 0 1-.606 1.9L18.15 23.99a.71.71 0 0 0 .17.993");
}

.wx648tb2b {
  stop-color: var(--svg-color--e2783c, #E2783C);
}

.x9jisjb_u {
  stop-color: var(--svg-color--e38f3c, #E38F3C);
  stop-opacity: 0;
}

.yb3xhwbhy {
  stop-color: var(--svg-color--d86443, #D86443);
}

.z-mdy21uz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M29.219 9.938v5.624c-.01 1.636-.657 5.638-3.157 8.563");
}

</style>
