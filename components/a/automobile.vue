<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ihhYwcn)"><path fill="url(#iLEvCHb)" class="zq0jmmdfj"/></g><path fill="url(#iC9nA9c)" class="zq0jmmdfj"/><g filter="url(#iNO4OJe)"><path clip-rule="evenodd" class="wh0nmebum"/></g><path fill="url(#iHAFCsd)" class="wewxdwbel"/><path fill="url(#iuYmB1d)" class="wewxdwbel"/><path fill="url(#i38Zbbb)" class="wewxdwbel"/><path fill="url(#i2bnNCe)" class="wewxdwbel"/><path class="ilfzbxb7p"/><path fill="url(#ikyq1ae)" class="dymp3on-j"/><path fill="url(#iYGHmyb)" class="dymp3on-j"/><path fill="url(#i4EkRnY)" class="dymp3on-j"/><g filter="url(#iCs8nJd)"><path fill="url(#irojiKd)" class="jf-h--b3x"/></g><path fill="url(#iKsSbhc)" class="ag0ro8bxy"/><path fill="url(#iAJUaxd)" class="ag0ro8bxy"/><path fill="url(#ieu0K9b)" class="ag0ro8bxy"/><path fill="url(#iwZH7Zd)" clip-rule="evenodd" class="b7_0z2lvq"/><path fill="url(#i9sUKde)" clip-rule="evenodd" class="o51q057bk"/><path class="hjpdwcbfp"/><g filter="url(#iS6agXb)"><path fill="url(#iY8vw6d)" class="gj1qo0a_s"/><path fill="url(#iYPYSpb)" class="gj1qo0a_s"/></g><g filter="url(#iaTDhrd)"><path class="qc1uwmb1z"/></g><path fill="url(#iFSMpSd)" class="az0844sdy"/><g filter="url(#iOko8sb)"><circle stroke="url(#itAvHVb)" class="intmgh5li"/></g><g filter="url(#ijmOulb)"><path fill="url(#iIWuaid)" class="v8fuqxh-f"/><path fill="url(#iAL0Pwc)" class="v8fuqxh-f"/></g><g filter="url(#i1bSTMc)"><path class="dhpa_bbpx"/></g><g filter="url(#illu7Ub)"><circle stroke="url(#iQK2WJd)" class="st0v1wbqg"/></g><path fill="url(#icYM7xc)" clip-rule="evenodd" class="xmdyldwgw"/><path fill="url(#iWXQcPc)" clip-rule="evenodd" class="xmdyldwgw"/><g filter="url(#isWkOfe)"><path fill="url(#iZNjQsc)" class="i1zlafbrp"/></g><defs><linearGradient id="iLEvCHb" x1="2.582" x2="17.27" y1="18.505" y2="18.505" gradientUnits="userSpaceOnUse"><stop class="nl6bpnb0h"/><stop offset="1" class="m52wtj66a"/></linearGradient><linearGradient id="iHAFCsd" x1="14.707" x2="9.145" y1="13.443" y2="18" gradientUnits="userSpaceOnUse"><stop class="of4uiab9g"/><stop offset="1" class="sf4-kl9rh"/></linearGradient><linearGradient id="iuYmB1d" x1="15.985" x2="14.145" y1="17.193" y2="17.193" gradientUnits="userSpaceOnUse"><stop class="h2p25cuot"/><stop offset="1" class="ln6uoptif"/></linearGradient><linearGradient id="i38Zbbb" x1="14.145" x2="14.145" y1="11.443" y2="17.255" gradientUnits="userSpaceOnUse"><stop offset=".226" class="h2p25cuot"/><stop offset="1" class="ln6uoptif"/></linearGradient><linearGradient id="i2bnNCe" x1="7.965" x2="11.975" y1="18" y2="18" gradientUnits="userSpaceOnUse"><stop class="io68o8bvw"/><stop offset=".653" class="gayh2kxsl"/><stop offset="1" class="i4qa-nmtf"/></linearGradient><linearGradient id="ikyq1ae" x1="1.995" x2="2.885" y1="25" y2="25" gradientUnits="userSpaceOnUse"><stop class="dmpkdq02m"/><stop offset="1" class="ic1tv_n5e"/></linearGradient><linearGradient id="iYGHmyb" x1="29.995" x2="28.43" y1="25" y2="25" gradientUnits="userSpaceOnUse"><stop class="dmpkdq02m"/><stop offset="1" class="ic1tv_n5e"/></linearGradient><linearGradient id="i4EkRnY" x1="15.995" x2="15.995" y1="26" y2="25.162" gradientUnits="userSpaceOnUse"><stop class="gqw9u5bxd"/><stop offset="1" class="qx7-w3a0p"/></linearGradient><linearGradient id="irojiKd" x1="21.957" x2="18.005" y1="13.943" y2="18.568" gradientUnits="userSpaceOnUse"><stop class="cot928cgw"/><stop offset="1" class="zw2h1obva"/></linearGradient><linearGradient id="iKsSbhc" x1="28.707" x2="25.645" y1="15" y2="18" gradientUnits="userSpaceOnUse"><stop class="x8avpn1nx"/><stop offset="1" class="cp65m-qgt"/></linearGradient><linearGradient id="iAJUaxd" x1="26.41" x2="27.098" y1="12.552" y2="13.318" gradientUnits="userSpaceOnUse"><stop class="g1j83-bop"/><stop offset="1" class="w44qgr5mc"/></linearGradient><linearGradient id="ieu0K9b" x1="30.239" x2="29.082" y1="18" y2="16.912" gradientUnits="userSpaceOnUse"><stop class="g1j83-bop"/><stop offset="1" class="w44qgr5mc"/></linearGradient><linearGradient id="iwZH7Zd" x1="8.495" x2="8.495" y1="21.531" y2="25.871" gradientUnits="userSpaceOnUse"><stop class="s04vvxdnk"/><stop offset="1" class="ol_2z3w3i"/></linearGradient><linearGradient id="i9sUKde" x1="23.495" x2="23.495" y1="21.531" y2="25.871" gradientUnits="userSpaceOnUse"><stop class="s04vvxdnk"/><stop offset="1" class="ol_2z3w3i"/></linearGradient><linearGradient id="iY8vw6d" x1="21.881" x2="27.138" y1="24.62" y2="24.62" gradientUnits="userSpaceOnUse"><stop offset=".239" class="baem9ki2q"/><stop offset="1" class="mmwl-dsmc"/></linearGradient><linearGradient id="itAvHVb" x1="25.102" x2="22.103" y1="23.234" y2="27.376" gradientUnits="userSpaceOnUse"><stop offset=".083" class="oeptinb4s"/><stop offset=".391" class="f0k16nibb"/><stop offset=".692" class="f0k16nibb"/><stop offset=".935" class="oeptinb4s"/></linearGradient><linearGradient id="iIWuaid" x1="6.901" x2="12.158" y1="24.62" y2="24.62" gradientUnits="userSpaceOnUse"><stop offset=".239" class="baem9ki2q"/><stop offset="1" class="mmwl-dsmc"/></linearGradient><linearGradient id="iQK2WJd" x1="10.04" x2="7.04" y1="23.234" y2="27.376" gradientUnits="userSpaceOnUse"><stop offset=".083" class="oeptinb4s"/><stop offset=".391" class="f0k16nibb"/><stop offset=".692" class="f0k16nibb"/><stop offset=".935" class="oeptinb4s"/></linearGradient><linearGradient id="iWXQcPc" x1="11.858" x2="12.175" y1="17.738" y2="17.738" gradientUnits="userSpaceOnUse"><stop class="pplpvl8bq"/><stop offset="1" class="nbtd6pb-j"/></linearGradient><filter id="ihhYwcn" width="28.5" height="14" x="1.495" y="10" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.137255 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10534"/></filter><filter id="iNO4OJe" width="2.823" height="3.901" x="9.622" y="15.895" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10534" stdDeviation=".2"/></filter><filter id="iCs8nJd" width="6.71" height="7" x="17.255" y="12" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75" dy="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.168627 0 0 0 0 0.45098 0 0 0 0 0.964706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10534"/></filter><filter id="iS6agXb" width="7" height="7.15" x="19.995" y="22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0823529 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10534"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.0313726 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10534" result="effect2_innerShadow_18_10534"/></filter><filter id="iaTDhrd" width="3.1" height="3.1" x="21.945" y="23.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.364706 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10534"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.764706 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10534" result="effect2_innerShadow_18_10534"/></filter><filter id="iOko8sb" width="7.287" height="7.287" x="20.113" y="21.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10534" stdDeviation=".375"/></filter><filter id="ijmOulb" width="7" height="7.15" x="5.015" y="22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0823529 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10534"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.0313726 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10534" result="effect2_innerShadow_18_10534"/></filter><filter id="i1bSTMc" width="3.1" height="3.1" x="6.945" y="23.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.364706 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10534"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.764706 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10534" result="effect2_innerShadow_18_10534"/></filter><filter id="illu7Ub" width="7.287" height="7.287" x="5.051" y="21.549" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10534" stdDeviation=".375"/></filter><filter id="isWkOfe" width="1.253" height="2.79" x="10.834" y="16.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10534" stdDeviation=".1"/></filter><radialGradient id="iC9nA9c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5779 1.5062 -2.64847 -2.77456 27.363 10.805)" gradientUnits="userSpaceOnUse"><stop class="u3w3vac9u"/><stop offset="1" class="yg9l_yfcp"/></radialGradient><radialGradient id="iYPYSpb" cx="0" cy="0" r="1" gradientTransform="matrix(.79083 -1.73826 1.81555 .826 23.495 25.187)" gradientUnits="userSpaceOnUse"><stop offset=".523" class="ariye-f8h"/><stop offset="1" class="a2peghb2c"/></radialGradient><radialGradient id="iFSMpSd" cx="0" cy="0" r="1" gradientTransform="rotate(-120.532 21.467 2.771)scale(2.61197)" gradientUnits="userSpaceOnUse"><stop offset=".418" class="je95jdh-g"/><stop offset="1" class="tsj-yeqgz"/></radialGradient><radialGradient id="iAL0Pwc" cx="0" cy="0" r="1" gradientTransform="matrix(.79083 -1.73826 1.81555 .826 8.515 25.187)" gradientUnits="userSpaceOnUse"><stop offset=".523" class="ariye-f8h"/><stop offset="1" class="a2peghb2c"/></radialGradient><radialGradient id="icYM7xc" cx="0" cy="0" r="1" gradientTransform="matrix(1.25 -1.30468 3.4823 3.33637 10.98 18.427)" gradientUnits="userSpaceOnUse"><stop class="xlx2dac6w"/><stop offset="1" class="nbtd6pb-j"/></radialGradient><radialGradient id="iZNjQsc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.24219 -.82422 0 11.887 16.372)" gradientUnits="userSpaceOnUse"><stop class="ieu7wlbzj"/><stop offset="1" class="fh8p3pn4n"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:automobile" /></template>
<style>
.a2peghb2c {
  stop-color: var(--svg-color--2b1249, #2B1249);
  stop-opacity: 0;
}

.ag0ro8bxy {
  d: path("m29.465 16.58l-1.64-4.37c-.02-.06-.09-.21-.09-.21h-.72c-.57 0-1.04.47-1.04 1.04v4c0 .53.43.96.96.96h2.91c-.08-.48-.21-.96-.38-1.42");
}

.ariye-f8h {
  stop-color: var(--svg-color--2d114d, #2D114D);
}

.az0844sdy {
  d: path("M29.985 20h-.5c-.85 0-1.54.71-1.5 1.57c.04.81.74 1.43 1.55 1.43h.45z");
}

.b7_0z2lvq {
  fill-rule: evenodd;
  d: path("M12.316 26q.045-.294.046-.602A3.867 3.867 0 1 0 4.674 26z");
}

.baem9ki2q {
  stop-color: var(--svg-color--34214f, #34214F);
}

.cot928cgw {
  stop-color: var(--svg-color--40a4ff, #40A4FF);
}

.cp65m-qgt {
  stop-color: var(--svg-color--4cf0f8, #4CF0F8);
}

.dhpa_bbpx {
  fill: var(--svg-color--d9c3f0, #D9C3F0);
  d: path("M8.495 27a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

.dmpkdq02m {
  stop-color: var(--svg-color--847f89, #847F89);
}

.dymp3on-j {
  d: path("M28.605 26H3.385c-.77 0-1.39-.62-1.39-1.39V24h28v.61c0 .77-.62 1.39-1.39 1.39");
}

.f0k16nibb {
  stop-color: var(--svg-color--615b6b, #615B6B);
  stop-opacity: 0;
}

.fh8p3pn4n {
  stop-color: var(--svg-color--5e5866, #5E5866);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g1j83-bop {
  stop-color: var(--svg-color--2588da, #2588DA);
}

.gayh2kxsl {
  stop-color: var(--svg-color--40acf4, #40ACF4);
}

.gj1qo0a_s {
  d: path("M23.495 29a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7");
}

.gqw9u5bxd {
  stop-color: var(--svg-color--734995, #734995);
}

.h2p25cuot {
  stop-color: var(--svg-color--2372d7, #2372D7);
}

.hjpdwcbfp {
  fill: var(--svg-color--f7da4c, #F7DA4C);
  d: path("M3.985 22v-1c0-.55-.45-1-1-1h-.85c-.1.29-.14.6-.14 1.27V23h.99c.55 0 1-.45 1-1");
}

.i1zlafbrp {
  d: path("M11.887 16.247v2.368c-.719-.563-.872-1.841-.851-2.313c.293-.106.69-.08.851-.055");
}

.i4qa-nmtf {
  stop-color: var(--svg-color--40acf4, #40ACF4);
  stop-opacity: 0;
}

.ic1tv_n5e {
  stop-color: var(--svg-color--847f89, #847F89);
  stop-opacity: 0;
}

.ieu7wlbzj {
  stop-color: var(--svg-color--5e5866, #5E5866);
}

.ilfzbxb7p {
  fill: var(--svg-color--9989aa, #9989AA);
  d: path("M28.605 26H3.385c-.77 0-1.39-.62-1.39-1.39V24h28v.61c0 .77-.62 1.39-1.39 1.39");
}

.intmgh5li {
  cx: 23.757px;
  cy: 25.193px;
  r: 2.469px;
  stroke-width: var(--svg-stroke-width--0-85px, 0.85px);
}

.io68o8bvw {
  stop-color: var(--svg-color--5eeeff, #5EEEFF);
}

.je95jdh-g {
  stop-color: var(--svg-color--d32374, #D32374);
}

.jf-h--b3x {
  d: path("M23.005 18h-4.04a.96.96 0 0 1-.96-.96v-4.08c0-.53.43-.96.96-.96h4.04c.53 0 .96.43.96.96v4.08c0 .53-.43.96-.96.96");
}

.ln6uoptif {
  stop-color: var(--svg-color--2372d7, #2372D7);
  stop-opacity: 0;
}

.m52wtj66a {
  stop-color: var(--svg-color--ed334e, #ED334E);
}

.mmwl-dsmc {
  stop-color: var(--svg-color--241337, #241337);
}

.nbtd6pb-j {
  stop-color: var(--svg-color--281f4a, #281F4A);
}

.nl6bpnb0h {
  stop-color: var(--svg-color--df378a, #DF378A);
}

.o51q057bk {
  fill-rule: evenodd;
  d: path("M27.316 26q.046-.294.046-.602a3.867 3.867 0 1 0-7.688.602z");
}

.oeptinb4s {
  stop-color: var(--svg-color--615b6b, #615B6B);
}

.of4uiab9g {
  stop-color: var(--svg-color--3398f0, #3398F0);
}

.ol_2z3w3i {
  stop-color: var(--svg-color--7e0b55, #7E0B55);
}

.pplpvl8bq {
  stop-color: var(--svg-color--281f4a, #281F4A);
  stop-opacity: 0;
}

.qc1uwmb1z {
  fill: var(--svg-color--d9c3f0, #D9C3F0);
  d: path("M23.495 27a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

.qx7-w3a0p {
  stop-color: var(--svg-color--734995, #734995);
  stop-opacity: 0;
}

.s04vvxdnk {
  stop-color: var(--svg-color--64023b, #64023B);
}

.sf4-kl9rh {
  stop-color: var(--svg-color--57e8ff, #57E8FF);
}

.st0v1wbqg {
  cx: 8.694px;
  cy: 25.193px;
  r: 2.469px;
  stroke-width: var(--svg-stroke-width--0-85px, 0.85px);
}

.tsj-yeqgz {
  stop-color: var(--svg-color--b60160, #B60160);
}

.u3w3vac9u {
  stop-color: var(--svg-color--ff4d5a, #FF4D5A);
}

.v8fuqxh-f {
  d: path("M8.515 29a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7");
}

.w44qgr5mc {
  stop-color: var(--svg-color--2588da, #2588DA);
  stop-opacity: 0;
}

.wewxdwbel {
  d: path("m11.995 12l-4.03 6h7.06c.53 0 .96-.43.96-.96v-4.08a.96.96 0 0 0-.96-.96z");
}

.wh0nmebum {
  fill: var(--svg-color--94154b, #94154B);
  fill-rule: evenodd;
  d: path("M10.022 17.846c.005-.293.07-.95.492-1.298c.272-.224.704-.274 1.058-.246c.295.024.473.286.473.573v1.94c0 .288-.178.55-.473.574c-.354.028-.786-.022-1.058-.246c-.421-.348-.487-1.005-.492-1.297");
}

.x8avpn1nx {
  stop-color: var(--svg-color--3da7ff, #3DA7FF);
}

.xlx2dac6w {
  stop-color: var(--svg-color--3a2557, #3A2557);
}

.xmdyldwgw {
  fill-rule: evenodd;
  d: path("M10.152 17.494c.005-.292.07-.95.492-1.297c.271-.225.703-.275 1.057-.247c.295.024.474.287.474.573v1.941c0 .287-.179.55-.474.573c-.354.028-.786-.021-1.058-.246c-.421-.348-.487-1.005-.491-1.297");
}

.yg9l_yfcp {
  stop-color: var(--svg-color--ff4d5a, #FF4D5A);
  stop-opacity: 0;
}

.zq0jmmdfj {
  d: path("M14.975 10h9.66c1.36 0 2.58.81 3.12 2.04l.005.014c.022.049.053.12.065.156l1.64 4.37c.168.456.297.93.378 1.406l.012.014c.09.49.14 1 .14 1.51V24h-28l.13-4c.37-1.16 1.46-2 2.75-2h3.1l4.37-6.51c.59-.88 1.57-1.45 2.63-1.49");
}

.zw2h1obva {
  stop-color: var(--svg-color--5bf6ff, #5BF6FF);
}

</style>
