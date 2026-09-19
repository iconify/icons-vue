<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iNvy4Zb)"><path fill="url(#iCYt7qd)" clip-rule="evenodd" class="g_kr-1e0u"/></g><g filter="url(#iMKxBpe)"><path class="qy03mdbfr"/></g><rect fill="url(#itqgPsP)" class="yx065ubfx"/><rect fill="url(#iKEOqCd)" class="yx065ubfx"/><rect fill="url(#ij6yNCc)" transform="matrix(0 -1 -1 0 30.276 7.75)" class="i_6orjl_t"/><rect fill="url(#iLtYCdb)" transform="matrix(0 -1 -1 0 30.276 7.75)" class="i_6orjl_t"/><g filter="url(#i3VuUVZ)"><rect transform="scale(-1 1)rotate(-45 -4.995 34.8)" class="d6-j_kbef"/></g><g filter="url(#ip4Isqc)"><rect fill="url(#irm3djd)" transform="scale(-1 1)rotate(-45 -4.949 34.32)" class="q40u_r7tl"/></g><g filter="url(#iiPG3fd)"><rect fill="url(#ihUV1kD)" class="fmb831w6w"/></g><g filter="url(#iUctsze)"><rect fill="url(#iE10MDc)" transform="rotate(90 30.115 6.978)" class="gy84cjhgo"/></g><defs><filter id="iNvy4Zb" width="27.719" height="27.562" x="2.14" y="2.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy=".2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.384314 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21265"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.215686 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_21265" result="effect2_innerShadow_18_21265"/></filter><filter id="iMKxBpe" width="7.66" height="7.149" x="12.962" y="11.37" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.592157 0 0 0 0 0.65098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21265"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.443137 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_21265" result="effect2_innerShadow_18_21265"/></filter><filter id="i3VuUVZ" width="1.424" height="1.674" x="24.437" y="5.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.396078 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21265"/></filter><filter id="ip4Isqc" width="1.332" height="1.332" x="24.579" y="6.166" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_21265" stdDeviation=".125"/></filter><filter id="iiPG3fd" width=".767" height="4.895" x="24.589" y="1.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_21265" stdDeviation=".125"/></filter><filter id="iUctsze" width="4.895" height=".767" x="25.471" y="6.728" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_21265" stdDeviation=".125"/></filter><radialGradient id="iKEOqCd" cx="0" cy="0" r="1" gradientTransform="matrix(-.82629 .70313 -.5039 -.59218 25.276 6.32)" gradientUnits="userSpaceOnUse"><stop offset=".421" class="qnq6w4b-y"/><stop offset="1" class="bewfm12cx"/></radialGradient><radialGradient id="iLtYCdb" cx="0" cy="0" r="1" gradientTransform="matrix(-.5625 .57813 -.27008 -.26278 .82 4.654)" gradientUnits="userSpaceOnUse"><stop class="f9wyz2n1l"/><stop offset="1" class="kpofg51br"/></radialGradient><radialGradient id="irm3djd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .88476 -1.57771 0 .137 -.137)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="f0puokwss"/><stop offset="1" class="s-iejzb6j"/></radialGradient><radialGradient id="iE10MDc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8136 -.26565 0 30.249 6.978)" gradientUnits="userSpaceOnUse"><stop offset=".135" class="f0puokwss"/><stop offset="1" class="s-iejzb6j"/></radialGradient><linearGradient id="iCYt7qd" x1="26.34" x2="8.84" y1="7.21" y2="24.523" gradientUnits="userSpaceOnUse"><stop class="k4f0cjtij"/><stop offset="1" class="dhbto2bla"/></linearGradient><linearGradient id="itqgPsP" x1="25.276" x2="24.268" y1="4.804" y2="4.804" gradientUnits="userSpaceOnUse"><stop class="mmq2utbuk"/><stop offset="1" class="zlfr6obxf"/></linearGradient><linearGradient id="ij6yNCc" x1="1.008" x2="0" y1="3.063" y2="3.063" gradientUnits="userSpaceOnUse"><stop class="dmn9oidau"/><stop offset="1" class="g_m71qbkr"/></linearGradient><linearGradient id="ihUV1kD" x1="24.972" x2="24.972" y1="2.06" y2="8.569" gradientUnits="userSpaceOnUse"><stop class="f0puokwss"/><stop offset="1" class="s-iejzb6j"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bookmark" /></template>
<style>
.bewfm12cx {
  stop-color: var(--svg-color--ca6533, #CA6533);
  stop-opacity: 0;
}

.d6-j_kbef {
  width: 1.008px;
  height: 1.597px;
  fill: var(--svg-color--cd7c3d, #CD7C3D);
  rx: 0.504px;
}

.dhbto2bla {
  stop-color: var(--svg-color--f0305c, #F0305C);
}

.dmn9oidau {
  stop-color: var(--svg-color--ce8149, #CE8149);
}

.f0puokwss {
  stop-color: var(--svg-color--d99666, #D99666);
}

.f9wyz2n1l {
  stop-color: var(--svg-color--cd6c36, #CD6C36);
}

.fmb831w6w {
  width: 0.267px;
  height: 4.395px;
  x: 24.839px;
  y: 2.06px;
  rx: 0.134px;
}

.ft5dv1b6b {
  fill: none;
}

.g_kr-1e0u {
  fill-rule: evenodd;
  d: path("M21.781 2.7a1.3 1.3 0 0 0-1.838 0L2.699 19.944a1.224 1.224 0 0 0 1.027 2.078l5.62-.748a1.25 1.25 0 0 1 1.4 1.425l-.84 5.567a1.232 1.232 0 0 0 2.088 1.054l17.285-17.284a1.3 1.3 0 0 0 0-1.839zm1.505 8.057c1.093 0 1.978-.899 1.978-2.008s-.885-2.008-1.978-2.008s-1.979.9-1.979 2.008s.886 2.008 1.979 2.008");
}

.g_m71qbkr {
  stop-color: var(--svg-color--d46f51, #D46F51);
}

.gy84cjhgo {
  width: 0.267px;
  height: 4.395px;
  x: 30.115px;
  y: 6.978px;
  rx: 0.134px;
}

.i_6orjl_t {
  width: 1.008px;
  height: 5.031px;
  rx: 0.504px;
}

.k4f0cjtij {
  stop-color: var(--svg-color--ff454e, #FF454E);
}

.kpofg51br {
  stop-color: var(--svg-color--cd6c36, #CD6C36);
  stop-opacity: 0;
}

.mmq2utbuk {
  stop-color: var(--svg-color--cf8b51, #CF8B51);
}

.q40u_r7tl {
  width: 0.274px;
  height: 1.064px;
  rx: 0.137px;
}

.qnq6w4b-y {
  stop-color: var(--svg-color--ca6533, #CA6533);
}

.qy03mdbfr {
  fill: var(--svg-color--ff85a2, #FF85A2);
  d: path("M18.943 12.339a.6.6 0 0 1 .734.747l-.388 1.325a.5.5 0 0 0 .063.417l.77 1.162a.6.6 0 0 1-.501.93H18.28a.5.5 0 0 0-.43.246l-.63 1.06a.6.6 0 0 1-1.069-.075l-.621-1.48a.5.5 0 0 0-.278-.273l-1.41-.554a.6.6 0 0 1-.11-1.06l1.12-.74a.5.5 0 0 0 .224-.396l.054-1.302a.6.6 0 0 1 .94-.468l1.1.762a.5.5 0 0 0 .417.07z");
}

.s-iejzb6j {
  stop-color: var(--svg-color--d99666, #D99666);
  stop-opacity: 0;
}

.yx065ubfx {
  width: 1.008px;
  height: 5.031px;
  x: 24.268px;
  y: 1.741px;
  rx: 0.504px;
}

.zlfr6obxf {
  stop-color: var(--svg-color--cb662e, #CB662E);
}

</style>
